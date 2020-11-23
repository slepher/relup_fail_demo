=== Desc ===  
Sample code to show how rebar3 relup fail on removed application module deps in appup.  
=== Usage ===  
git checkout v0.1.0  
rebar3 compile  
rebar3 release  
git checkout master  
rebar3 compile  
rebar3 release  
rebar3 relup -n release_a -v 0.2.0 -v 0.1.0  

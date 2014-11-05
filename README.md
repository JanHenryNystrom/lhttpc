lhttpc [(γ)][1] [![Build Status](https://secure.travis-ci.org/JanHenryNystrom/lhttpc.png)](http://travis-ci.org/JanHenryNystrom/lhttpc)

This is project that consists of a fork of the https://github.com/esl/lhttpc project that has been discontinued.
This project will be supported. It now works with R17.3
More to come..

Configuration: (environment variables)
 * connection_timeout: The time (in milliseconds) the client will try to
                       kepp a HTTP/1.1 connection open. Changing this value
                       in runtime has no effect, this can however be done
                       through lhttpc_manager:update_connection_timeout/1.

[1]: http://en.wikipedia.org/wiki/Software_release_life_cycle
       "Software release life cycle"

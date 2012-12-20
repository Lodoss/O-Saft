 /~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~.
                                                                                )
	O-Saft  - OWASP SSL audit for testers                                  (
                                                                                )
  _-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_.
(
 )  DESCRIPTION
(       This tools lists  information about remote target's  SSL  certificate
 )      and tests the remote target according given list of ciphers.
(
 )  WHY?
(       Why a new tool for checking SSL  when there already exist a dozens or
 )      more in 2012? Some (but not all) reasons are:
(       * lack of tests of unusual ciphers
 )      * different results returned for the same check on same target
(       * missing functionality (checks) according modern SSL/TLS
 )      * lack of tests of unusual (SSL, certificate) configurations
(       * (mainly) missing feasability to add own tests
 )
(       For more details, please use
 )        o-saft.pl --help
(       or read the source ;-)
 )
(
 )  TARGET AUDIENCE
(       * penetration testers
 )      * administrators
(
 )  QUICK START
(       o-saft.pl --help
 )      o-saft.pl +check your.tld
(       more o-saft.pl
 )
(       Project home is http://www.owasp.org/index.php/Category:O-Saft_Project
 )
(
 )  Get a Copy
(       git clone git@github.com:OWASP/O-Saft.git
 )      git clone https://github.com:OWASP/O-Saft.git
(       wget https://github.com/OWASP/O-Saft/archive/master.zip
 \_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_-~-_/

# Web Hackers Handbook Notes

## Ch1-3
----

### Issues/counter measures:
* uncontrollable user input
    * white/black listing
    * sanitizing - e.g. url encoding
    * safe data processing - e.g. parameterized queries for sql
    * semantic checks - e.g. verify data submitted "belongs" to the user (previous were, in some sense, stateless, this could/would be stateful
    * Boundary validation - break up validation based on the components that process it, this can make potentially impossible validation possible (e.g. different components need to validate/sanitize in conflicting ways, rather than doing everything at the "front door" break up the checks as the data moves from one component to another)
* access control
    * authentication
    * session management
    * "straight up" access control (e.g. to backend data/resources)
* identifying and alerting about attacks and attackers
    * graceful error handling
    * logs - appropriate to the sensitivity of the activity, etc
    * Alerts to admins/ops
    * "reacting" ?? automated?
* application management access control
    * this is called out in the text, but is redundant (i.e. no new problems here, just a different place they might exist)

* additional info
    * multistep validation (or evasion) - e.g. remove `<script>` from `<scr<script>ipt>`
        
### Web Technologies
* HTTP
    * Methods
        * HEAD - returns only headers (that would normally be returned)
        * TRACE - return the exact request message in the response body
        * OPTIONS - server supplies supported methods (for the requested resource)
        * PUT - upload "stuff?"

* Web Functionality
    
        

  
  
  
  

USAGE:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXTRACT&nbsp;series&nbsp;width&nbsp;/index&nbsp;pos&nbsp;/default&nbsp;value&nbsp;/into&nbsp;output&nbsp;/local&nbsp;len&nbsp;val  
  
DESCRIPTION:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Extracts&nbsp;a&nbsp;value&nbsp;from&nbsp;a&nbsp;series&nbsp;at&nbsp;regular&nbsp;intervals.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXTRACT&nbsp;is&nbsp;a&nbsp;function&nbsp;.  
  
RETURNS:  
&nbsp;&nbsp;&nbsp;&nbsp;(undocumented)  
  
ARGUMENTS:  
&nbsp;&nbsp;&nbsp;&nbsp;series&nbsp;[any-series!]  
&nbsp;&nbsp;&nbsp;&nbsp;width&nbsp;[integer!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Size&nbsp;of&nbsp;each&nbsp;entry&nbsp;(the&nbsp;skip)  
  
REFINEMENTS:  
&nbsp;&nbsp;&nbsp;&nbsp;/index  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Extract&nbsp;from&nbsp;an&nbsp;offset&nbsp;position  
&nbsp;&nbsp;&nbsp;&nbsp;pos&nbsp;[any-number!&nbsp;logic!&nbsp;block!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The&nbsp;position(s)  
&nbsp;&nbsp;&nbsp;&nbsp;/default  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Use&nbsp;a&nbsp;default&nbsp;value&nbsp;instead&nbsp;of&nbsp;blank  
&nbsp;&nbsp;&nbsp;&nbsp;value  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The&nbsp;value&nbsp;to&nbsp;use&nbsp;(will&nbsp;be&nbsp;called&nbsp;each&nbsp;time&nbsp;if&nbsp;a&nbsp;function)  
&nbsp;&nbsp;&nbsp;&nbsp;/into  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Insert&nbsp;into&nbsp;a&nbsp;buffer&nbsp;instead&nbsp;(returns&nbsp;position&nbsp;after&nbsp;insert)  
&nbsp;&nbsp;&nbsp;&nbsp;output&nbsp;[any-series!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The&nbsp;buffer&nbsp;series&nbsp;(modified)  
&nbsp;&nbsp;&nbsp;&nbsp;/local  
&nbsp;&nbsp;&nbsp;&nbsp;len  
&nbsp;&nbsp;&nbsp;&nbsp;val  

[Rebol.com docs](http://www.rebol.com/r3/docs/functions/extract.html)
___
Above this line is autogenerated. Place user comments below.
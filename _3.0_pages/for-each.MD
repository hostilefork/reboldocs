USAGE:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FOR-EACH&nbsp;'vars&nbsp;data&nbsp;body&nbsp;  
  
DESCRIPTION:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Evaluates&nbsp;a&nbsp;block&nbsp;for&nbsp;each&nbsp;value(s)&nbsp;in&nbsp;a&nbsp;series.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FOR-EACH&nbsp;is&nbsp;a&nbsp;function&nbsp;.  
  
RETURNS:&nbsp;[&lt;opt&gt;&nbsp;any-value!]  
&nbsp;&nbsp;&nbsp;&nbsp;Last&nbsp;body&nbsp;result&nbsp;or&nbsp;BREAK&nbsp;value,&nbsp;will&nbsp;also&nbsp;be&nbsp;void&nbsp;if&nbsp;never&nbsp;run  
  
ARGUMENTS:  
&nbsp;&nbsp;&nbsp;&nbsp;'vars&nbsp;[word!&nbsp;block!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Word&nbsp;or&nbsp;block&nbsp;of&nbsp;words&nbsp;to&nbsp;set&nbsp;each&nbsp;time&nbsp;(local)  
&nbsp;&nbsp;&nbsp;&nbsp;data&nbsp;[any-series!&nbsp;any-context!&nbsp;map!&nbsp;blank!&nbsp;datatype!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The&nbsp;series&nbsp;to&nbsp;traverse  
&nbsp;&nbsp;&nbsp;&nbsp;body&nbsp;[block!]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Block&nbsp;to&nbsp;evaluate&nbsp;each&nbsp;time  
___
Above this line is autogenerated. Place user comments below.
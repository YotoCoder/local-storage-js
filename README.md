<b><p>This library helps to use javascript's localStorage in an easier way.</p></b>

New object:<br>
  <code>
  let cart = new Local('item')
  </code><br><br>
Add var in array:<br>
<code>
  cart.add({'id':1})
 </code><br><br>
Get data:<br>
  <code>
  cart.get()
  </code><br><br>
  <code>#output</code>
  <code>
    [{…}]<br><br>
    0: {id: 1}
  </code>
    
Delete:<br>
<code>
  cart.delete(1)
</code>

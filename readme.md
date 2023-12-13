<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script src="script.js"></script>
  </head>
  <body></body>
</html>

<h2>Array Methods</h2>
<h3>Array length</h3>
<p>
  This is majorly used to find the length of an array by calling array.length
</p>
<p>Other uses includes:</p>

<ul>
  <li>
    Getting the last item in an array using (array.length - 1) due to the zero
    indexed nature of array
  </li>
  <li>
    Increasing or reducing the length of an array by passing a number lower or
    higher than the original length. <br />
    With increasing length it adds empty items in the added index place while
    reducing length will remove existing items occupying index outside of the
    array.length value
  </li>
  <li>Adding items to an array using the array.length method as an index</li>
</ul>

<h3>array.toString and array.join method</h3>
<p>
  both methods are used to turn an array into a string of items separated by
  commas by default. The difference is the join method allows us to specify what
  we want to use to separate the string of items asides the default commas while
  toString() doesnt offer that option
</p>
<p>Example of method toString()</p>
<p>
  const arrays = ['red', 'blue', 'white'] <br />

arrays.toString() = red,blue,white

</p>
<p>Example of method join()</p>
<p>
  const arrays = ['red', 'blue', 'white'] <br />

arrays.join(+) = red+blue+white

</p>

<h3>array.pop and array.shift method</h3>
<p>
  Both methods are used to remove items from an array. However, the pop method
  remove the last item while the shift method removes the first item of the
  array. pop method also returns the value that was removed from the array
</p>
<h3>array.push and array.unshift method</h3>
<p>
  Both methods are used to add items to an array. However, the push method adds
  a new item to the end while the unshift method adds the new item to the
  beginning of the array
</p>

<h3>array.concat method</h3>
<p>
  concat() method is used to merge an existing array into a new array. The new
  items or array to be concatenated is passed as an argument inside the concat
  and a completely new array is created.
</p>

<h3>Delete()</h3>
<p>
  This deletes an item from the array but unlike pop and shift method, the
  delete is called as a keyword and the item to be deleted is passed as an
  index.
</p>
<p>
  It is not adviseable to use because this method will leave the index of the
  deleted item with an empty item which is undefined.
</p>

<h3>slice() method</h3>
<p>
  This helps us to slice or cut out parts of our array to form a new array. This
  method doesnt alter the original array that was sliced. You simply specify the
  index of the item that you want to slice out
</p>
<p>
  slice() method can take two argument, the first being the index from which to
  start the cut and the second is the index where the cut should end but will
  not include the item in the last index specified. If the second argument is
  not specified then the slice cut up to the end of the array to form a new
  array
</p>

<h3>Splice() method</h3>
<p>
  This removes items from an array without leaving holes and empty values in it.
  It also allows removing more than one item at the same time
</p>
<p>
  The splice () method can take two arguments. The first is the index where the
  item to be deleted is and the second is the number of items to be removed. If
  the second argument isnt specified then it removes from the first argument to
  the end of the array
</p>

<h3>Automatic toString()</h3>
<p>
  By default javscript automatically converts an array to strings separated by
  commas when the primitive string value is needed
</p>

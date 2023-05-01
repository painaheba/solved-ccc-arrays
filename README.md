Download Link: https://assignmentchef.com/product/solved-ccc-arrays
<br>
Arrays are a series of elements consisting of the same type (For ex: all integers or all floats), in a contiguous chunk of memory. The elements can be individually referenced by indexing the array. They are variables that can have multiple elements. Some of the important aspects of array are:

<ul>

 <li> You must specify the type of data stored in an array, and each element in any array must be of the same type.</li>

 <li> An array has a static size — they cannot grow any larger than the size you tell it to be when you create it.
 <strong>To access the value at a certain index of the array: </strong>for (int i = 0; i &lt; 10; i++){
 intArray[i] = i; //allows the value to be updated at each index cout&lt;&lt; intArray[i] &lt;&lt; endl; //prints the value at each index of the array
 }
 <strong>To access the memory address</strong> <strong>of the array element: </strong>for (int i = 0; i &lt; 10; i++){
 cout &lt;&lt; intArray + i &lt;&lt; endl; //prints the address }
 <strong>Example: </strong> This shows us an example of an array with 5 elements and how the computer starts as 0 for counting.</li>

</ul>




<strong>Creating and Initializing the Array </strong>

When you declare an array, you will get an uninitialized section of memory. If you want to create an array of numbers, you would do: For ex: int arrayName[arraySize];

<ul>

 <li> int intNumbers [10];</li>

 <li> double dbNumbers[10];
 Then, putting elements in the array can be set up by using the index of the array element you want to change: Note: This isn’t very efficient if you have a large array, but this is the idea.
 intNumbers[0] = 3; intNumbers[1] = 5; intNumbers[2] = 6; intNumbers[3] = 8;
 When you create an array, you do so to capture a group of items that all need to be treated separately, but also need to grouped together for some purpose. For example, when you think about a song, each note in the song is a separate sound, but they all need to be included together in a certain order to make up the song.
 <strong>To initialize the array: </strong> int intNum [5] = {16, 3, 20, 4, 21}; Hint: notice the syntax difference initializing this array versus the one above. It is very close.
 <strong>Retrieving/Adding/Changing elements </strong> To <em>access or retrieve </em>individual elements in an array intNumbers[0]; will be the first item in the intNumbers array.
 intNumbers[1]; will be the second item in the intNumbers array.
 We can <em>change or update </em>the values in the array using the index of the individual items, such as:</li>

</ul>




<strong>Example 1: </strong>

intNumber[1] = 10;

<strong>Example 2: </strong>

int intNumbers[2];

intNumbers[0] = 5; intNumbers[1] = 7; intNumbers[1] = intNumbers[1] * 2

cout &lt;&lt; intNumbers[1] &lt;&lt; endl;

<strong>Example 3: </strong>

for (int i = 0; i &lt; 10; i++){ intArray[i] = i;

cout &lt;&lt; intArray[i] &lt;&lt; endl;

}

<strong><em>HomeWork Activity: </em></strong>

//this updates the value to 10 at that index

//initializes //updates

//What value is printed?

//Sets what the values are in that position //prints out the value of i at each index




<ol>

 <li>Create an array of 20 doubles. Assign values to your array using a for loop, where myDoubles is the name of the array created.</li>

</ol>

2) Print out the values using another for loop.

3) Now, using your array and another loop, calculate the average of the values in the myDoubles array and print out the average using the statement below:

“The average value of myDoubles is: X” <em>(</em> <em>Hint: the answer should be 9.5) </em>



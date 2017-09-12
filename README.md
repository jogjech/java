### String
`String` is immutable in java. If we want to do for-each loop to every character in a String, we need to do
```
for (char ch: "xyz".toCharArray()) {
}
```
`public String substring(int startIndex)`: This method returns new String object containing the substring of the given string from specified startIndex (inclusive).

`public String substring(int startIndex, int endIndex)`: This method returns new String object containing the substring of the given string from specified startIndex to endIndex.


### Loop
If looping through `int[] nums`,

  `for (int i = 0; i < nums.length; i += 2) {...}`

### Sort
`Arrays.sort(nums);`

### ArrayList
`add(E e)`: Appends the specified element to the end of this list.

`add(int index, E element)`: Inserts the specified element at the specified position in this list.

`set(int index, E element)`:
Replaces the element at the specified position in this list with the specified element.

`boolean	addAll(Collection<? extends E> c)`:
Appends all of the elements in the specified collection to the end of this list, in the order that they are returned by the specified collection's Iterator.

`boolean	addAll(int index, Collection<? extends E> c)`:
Inserts all of the elements in the specified collection into this list, starting at the specified position.

`List<E>	subList(int fromIndex, int toIndex)`:
Returns a view of the portion of this list between the specified fromIndex, inclusive, and toIndex, exclusive.

Note: `Arrays.asList(x, y, z)` will return a fixed-size list. If we want to modify the list, we need to do `new ArrayList(Arrays.asList(...))` or `new LinkedList(Arrays.asList(...))`.

### HashMap
`boolean containsKey(Object key)`:
Returns true if this map contains a mapping for the specified key.

`boolean	containsValue(Object value)`:
Returns true if this map maps one or more keys to the specified value.

`V	put(K key, V value)`:
Associates the specified value with the specified key in this map.

### Priority Queue (`PriorityQueue`)
`offer(E e)`: Inserts the specified element into this priority queue.

`peek()`:
Retrieves, but does not remove, the head of this queue, or returns null if this queue is empty.

`poll()`:
Retrieves and removes the head of this queue, or returns null if this queue is empty.


### Stack (`Stack<Integer> s = new Stack<>();`)
1. `Object push(Object element)`:Pushes an element on the top of the stack.

2. `Object pop()`: Removes and returns the top element of the stack. An ‘EmptyStackException’ exception is thrown if we call pop() when the invoking stack is empty.

3. `Object peek( )`: Returns the element on the top of the stack, but does not remove it.

4. `boolean empty()`: It returns true if nothing is on the top of the stack. Else, returns false.

5. `int search(Object element)`: It determines whether an object exists in the stack. If the element is found, it returns the position of the element from the top of the stack. Else, it returns -1.


### Tree
```
public class TreeNode {
    int val;
    TreeNode left;
    TreeNode right;
    TreeNode(int x) { val = x; }
}
```

### LinkedList
```
public class lc.ListNode {
      int val;
      lc.ListNode next;
      lc.ListNode(int x) { val = x; }
}
```

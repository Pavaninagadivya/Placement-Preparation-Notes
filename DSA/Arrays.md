# Arrays

## What is an Array?

An array is a collection of elements of the same data type stored in contiguous memory locations. Each element is accessed using its index.

---

## Java

### Declaration

```java
int[] arr;
```

### Initialization

```java
int[] arr = {1, 2, 3, 4, 5};
```

### Accessing Elements

```java
System.out.println(arr[0]);
```

---

## Python

### Creating an Array (Using List)

```python
arr = [1, 2, 3, 4, 5]
```

### Accessing Elements

```python
print(arr[0])
```

### Updating Elements

```python
arr[2] = 10
print(arr)
```

---

## Time Complexity

| Operation | Complexity |
|-----------|------------|
| Access | O(1) |
| Search | O(n) |
| Update | O(1) |
| Insert | O(n) |
| Delete | O(n) |

---

## Advantages

- Fast access using index
- Easy to traverse
- Memory efficient

---

## Disadvantages

- Fixed size in Java
- Insertion and deletion are costly




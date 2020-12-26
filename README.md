# rust-lists
Learn Rust by writing linked lists.

![Rust](https://github.com/dexterdarwich/rust-lists/workflows/Rust/badge.svg)

## Background
While learning Rust, I decided to follow this great resource [Learn Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/).


## A Bad Stack
Singly-Linked Stack, that implements:
* New - Create a new list.
* Push - Push an element onto the stack.
* Pop - Remove an element from the head of the stack.
* Drop - Implemented the drop trait to clean up iteratively.
* Added tests.

## An Ok Stack
An Ok Singly-Linked Stack
* Deinvent the wheel
* Make the list generic
* Add peeking
* Make the list iterable

## A Persistent Stack
A Persistent Singly-Linked Stack
* Shared Ownership
* Immutable singly-linked list
* Rust Rc and Arc

## A Bad Safe Deque
A Bad Safe Doubly-Linked Deque
* Doubly Linked List
* Interior Mutability

## An Unsafe Queue
An Unsafe singly linked Queue
* Raw pointers and Unsafe Rust
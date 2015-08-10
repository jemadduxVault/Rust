## Rust Notes

Memory management in Rust.

The stack vs the heap. THe stack is fast and is the default location that memory is allocated in Rust. This allocation is "local to a function call and limited in size." The heap is slower but doesn't have a size limit and is globally accessible.

Ownership of the memory is the concept in Rust that means there is no need for garbage collection. When a variable goes out of scope then the memory associated with it will be deallocated and this is done by the compiler. So the programmer doesn't need to insert 'malloc' and 'free' themselves, the compiler with figure it out. 

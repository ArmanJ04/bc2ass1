## Sorting Library
This is a Rust library crate that provides sorting algorithms such as quicksort, selection sort, insertion sort, and merge sort for various types of objects.
## Usage
To use this library, simply add it as a dependency in your `Cargo.toml` file:
```toml
[dependencies]
sorting_library = { git = "https://github.com/ArmanJ04/bc2ass1" }
```
![Screenshot 2024-04-20 163938](https://github.com/ArmanJ04/bc2ass1/assets/57132784/63e1a81e-4fdd-47d1-91eb-944aecec60cd)

## Example
This my code for sorting using library
```
use sorting_library::{Sortable, quick_sort, selection_sort, insertion_sort, merge_sort};

fn main() {
    let mut nums = vec![5, 3, 8, 1, 6];
    quick_sort(&mut nums);
    println!("Quicksort: {:?}", nums);
    selection_sort(&mut nums);
    println!("Selection Sort: {:?}", nums);
    insertion_sort(&mut nums);
    println!("Insertion Sort: {:?}", nums);
    merge_sort(&mut nums);
    println!("Merge Sort: {:?}", nums);
}
```
## Licence
This project is not licensed.


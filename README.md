# Fast Diff

General purpose, fast diff algorithm supporting [m] level nested diffs.  

## Why?
1. Most diffing algorithm are O(nlogn) or O(n.m) 
2. Most algorithm solve Least Common Subsequence problem which is hard to grasp at first
3. Supports nested diffing as per requirement.

## Running the tests

Go to the source directory, and run:
```swift
$ swift test
```

## Contributing

Feel free to contribute with Pull Requests. There are many tasks (trivial) left to do. 

### Potential Tasks
- Cocoapods support
- Documentation grammar correction
- Adding CI and build status

## Authors

At the moment, solely me:
1. @kandelvijaya

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspired by Paul Heckel's paper & algorithm 

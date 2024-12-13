# Race Condition in Go Concurrent Counter

This repository demonstrates a common race condition in Go programs that involve concurrent access to shared resources.  The `bug.go` file contains code that attempts to increment a counter using multiple goroutines. Due to the lack of proper synchronization mechanisms, the final count may be less than expected.

The `bugSolution.go` file provides a corrected version that uses a mutex to prevent race conditions and ensure the counter is incremented correctly.

This example highlights the importance of proper synchronization when working with concurrent programming in Go.
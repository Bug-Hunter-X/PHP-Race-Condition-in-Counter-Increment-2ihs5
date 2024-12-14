# PHP Race Condition Example

This repository demonstrates a simple race condition in PHP.  The `bug.php` file contains code that increments a global counter.  Without proper synchronization mechanisms, concurrent requests can lead to incorrect counter values.  The solution is provided in `bugSolution.php`, employing a mutex lock for thread-safe increment.
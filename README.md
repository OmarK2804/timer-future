# Module 10 - Asynchoronous Programming

## 1.2. Understanding how it works.

![](imgfiles/Screenshot%202024-05-07%20132707.png)

The line `Omar's Komputer: done!` is printed first because it is a synchronous operation in the main() function, executed before the asynchronous task is run by executor.

## 1.3. Multiple Spawn and removing drop

### Put drop(spawner);
![](imgfiles/Screenshot%202024-05-07%20134704.png)
### Remove drop(spawner);
![](imgfiles/Screenshot%202024-05-07%20134634.png)

If the `drop(spawner);` statement is removed, the executor keep running because it's still expecting more task thus the program wont terminate in the terminal.
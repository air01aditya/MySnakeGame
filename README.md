# MySnakeGame

Snake in the Windows terminal, written in C++. The snake's body is a queue I wrote myself.

| Start | Game over |
|:---:|:---:|
| ![Start](Game%20begins.png) | ![Game over](Game%20over.png) |

## Run it

Needs `g++` (for example MinGW-w64).

```bash
g++ -std=c++17 SnakeGame.cpp Snake.cpp -o MySnakeGame.exe
MySnakeGame.exe
```

## License

[MIT](LICENSE)

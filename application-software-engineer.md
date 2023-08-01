# Q1

What's the time complexity of the following code, and why?

```dart
int r = 0;
for (var i = 0; i < N; i++) {
  for (var j = i; j < N; j++) {
    r = r + 1;
  }
}
```

# Q2

Please design a series of RESTful-style APIs to implement:
- Adding product(s)
- Obtaining product information
- Updating product information
- Removing product(s)

# Q3

Consider the following Dart code, is there anything unreasonable or wrong in it? If so, how should it be modified to make it work as expected?

```dart
void main() async {
  final socket = await Socket.connect('<ipv4-address>', /* valid port */);
  observeType1DataOf(socket);
  observeType2DataOf(socket);
}

void observeType1DataOf(Socket s) {
  s.listen((chunk) {
    print(chunk);
  });
}

void observeType2DataOf(Socket s) {
  s.listen((chunk) {
    print(chunk);
  });
}
```
# Q4

Please use Dart to implement a program that parses the following DSL and extracts valid information into memory (you can freely design the memory data structure):

```html
<Robot>
  <Model>Cartesius<Model>
  <Version>20230729</Version>
  <Build>809dxcv90j1nolqjk</Build>
</Robot>
```

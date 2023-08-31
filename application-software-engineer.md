# Application software engineer

Hi 👋, Thank you for choosing our team.

Here are some questions to examine the basics and necessary programming knowledge, and you can answer them in any way you like (we recommend using a plain text format, such as Markdown).

In addition, please try not to use external tools during the answering process, because these questions are all derived from real work scenarios.

Ready? Then let's get started!

## Q1

What's the time complexity of the following code, and why?

```dart
int r = 0;
for (var i = 0; i < N; i++) {
  for (var j = i; j < N; j++) {
    r = r + 1;
  }
}
```

## Q2

Please design a series of RESTful-style APIs to implement:
- Adding product(s)
- Obtaining product information
- Updating product information
- Removing product(s)

## Q3

Consider the following Dart code, is there anything unreasonable or wrong in it? If so, how should it be modified to make it work as expected?

```dart
import 'dart:io';

void main() async {
  final socket = await Socket.connect(
    /* valid ipv4 address */,
    /* valid port */
  );
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
## Q4

Please use Dart to implement a program that parses the following DSL and extracts valid information into memory:

```html
<Robot>
  <Model>Cartesius</Model>
  <Version>20230729</Version>
  <Build>809dxcv90j1nolqjk</Build>
</Robot>
```

- You can freely design the memory data structure.
- It would be better if you can complete this problem without relying on any third-party library.


# Finally

We would like to sincerely thank you for your time and please send your answers to software-hiring@cartesiusrobotics.com when you are done.

Good luck and looking forward to being a colleague with you. 🎉

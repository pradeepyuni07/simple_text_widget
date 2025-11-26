# simple_text_widget

A simple Flutter package for a customizable Text widget.  
This package allows you to quickly display text with custom font size and color.

## Features

- Simple usage
- Customizable font size
- Customizable text color

## Usage

import 'package:flutter/material.dart';
import 'package:simple_text_widget/simple_text_widget.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(title: const Text('SimpleText Example')),
        body: Center(
          child: SimpleText(
            text: "Hello from Package!",
            fontSize: 24,
            color: Colors.blue,
          ),
        ),
      ),
    );
  }
}

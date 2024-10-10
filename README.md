import 'package:digi_tooth/mainscreen.dart';
import 'package:flutter/material.dart';

class register extends StatelessWidget {
  const register({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      routes: {
        '/details': (context) => mainscreen()
      },
      home: Scaffold(
        appBar: AppBar(
          title: Center(child: Text('Register ')),

        ),
      )
    );
  }
}

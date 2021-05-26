import 'package:flutter/cupertino.dart';
import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
        //comment
        // ! lash hak msawi
        // ? msh fahem
        // * ishi mohem
        title: 'App Image',
        debugShowCheckedModeBanner: false,
        home: Scaffold(
            appBar: AppBar(
              title: Text('App Images'),
              centerTitle: true,
            ),
            body: Image.asset('assets/Images/car.jpg')));
  }
}
/* Image.network(
              'https://ichef.bbci.co.uk/news/976/cpsprodpb/C448/production/_117684205_lotus.jpg'),*/


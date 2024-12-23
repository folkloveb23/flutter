import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    title: "Profile",
    theme: ThemeData(
      primarySwatch: Colors.blue,
      textTheme: TextTheme(
        bodyLarge: TextStyle(fontSize: 18, color: Colors.black87),
        bodyMedium: TextStyle(fontSize: 16, color: Colors.black54),
      ),
    ),
    home: Scaffold(
      appBar: AppBar(
        title: Text("Profile"),
        centerTitle: true,
      ),
      body: SingleChildScrollView(
        child: Padding(
          padding: const EdgeInsets.all(20.0),
          child: Column(
            crossAxisAlignment: CrossAxisAlignment.center,
            children: [
              CircleAvatar(
                radius: 80,
                backgroundImage: AssetImage("assets/images/folk.jpg"),
              ),
              SizedBox(height: 20),
              Text(
                "Saringkan Saleesoon (Folk)",
                style: TextStyle(fontSize: 24, fontWeight: FontWeight.bold, color: Colors.blueAccent),
                textAlign: TextAlign.center,
              ),
              Divider(height: 40, thickness: 2),
              Align(
                alignment: Alignment.centerLeft,
                child: Column(
                  crossAxisAlignment: CrossAxisAlignment.start,
                  children: [
                    Text("Hobbies:", style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
                    Text("- Sleep", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    Text("- Play games", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    Text("- Movies", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    SizedBox(height: 20),
                    Text("Favorite Foods:", style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
                    Text("- Shabu", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    Text("- Pad Ka Prao", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    Text("- Everything", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    SizedBox(height: 20),
                    Text("Birthplace:", style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
                    Text("Uttaradit", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    Divider(height: 40, thickness: 2),
                    Text("Education:", style: TextStyle(fontSize: 20, fontWeight: FontWeight.bold)),
                    Text("- Elementary: Bannaimuang School (Year: 7)", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    Text("- Primary: Phichai School (Year: 13)", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    Text("- High School: Phichai School (Year: 16)", style: TextStyle(fontSize: 16, color: Colors.black54)),
                    Text("- Undergrad: Naresuan University (Year: 19)", style: TextStyle(fontSize: 16, color: Colors.black54)),
                  ],
                ),
              )
            ],
          ),
        ),
      ),
    ),
  ));
}

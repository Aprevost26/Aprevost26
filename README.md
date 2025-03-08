# Task 1 - JavaScript Basics Task
 
 ![Alt text](https://github.com/user-attachments/assets/f3ec0beb-dd34-4d7c-a99a-92aab93bd3a9)
 
 **Exercises Overview:**
 
 1. Calculate the area of a rectangle 
 2. Calculate the diameter, circumference and area of a circle
 3. Find the third angle of a triangle given two angles
 4. Calculate the difference between two dates in days
 5. Display name initials in uppercase
 
 ## 1. Calculate the area of a rectangle 
 **Code**:
 ```
 let length = 5;
 let width = 3;
 let areaReactangle = length * width;
 
 console.log('Area of Reactangle: ');
 console.log(`Length: ${length}, Width: ${width} → Area = ${areaReactangle}`);
 ```
 
 **Output:**
 > Area of Reactangle: ↴ 
 > Length: 5, Width: 3 → Area = 15
 
 ## 2. Calculate diameter, Circumference and Area of a circle
 **Code:**
 ```
 let r = 5;
 let d = 2 * r;
 let pi = 3.141592653589793
 let circumference = pi * d;
 let area_circle = pi * r * r;
 let area_circle_fixed = Math.floor(area_circle * 1000) / 1000;
 
 console.log("Circle Properties: ↴");
 console.log(`Radius: ${r} → Diameter: ${d}, Circumference: ${circumference.toFixed(4)}, Area: ${area_circle_fixed}`);
 ```
 
 **Output:**
 > Circle Properties: ↴
 >
 > Radius: 5 → Diameter: 10, Circumference: 31.4159, Area: 78.539
 
 ## 3. Find the third angle of a triangle given two angles
 **Code:**
 ```
 let a, b, c;
 
 a = 80;
 b = 65;
 c = 180 - (a + b);
 
 console.log(`Given angles: a = ${a}°, b = ${b}° → The third angle is: ${c}°`);
 ```
 
 **Output:**
 > Given angles: a = 80°, b = 65° → The third angle is: 35°
 
 ## 4. Calculate the difference between two dates in days
 **Code:**
 ```
 let date1 = new Date("2024-03-19");
    let date2 = new Date("2024-03-21");
 
 let Difference_In_Time = date2.getTime() - date1.getTime();
 let Difference_In_Days = Math.round (Difference_In_Time / (1000 * 3600 * 24));
 
 console.log(`Days difference between ${date1.toDateString()} and ${date2.toDateString()} → ${Difference_In_Days} days`);
 ```
 **Output:**
 
 > Days difference between Mar 19 2024 and Mar 21 2024 → is 2 days
 
 ## 5. Display name initials in uppercase
 **Code:**
 ```
 const s1 = "John Doe";
 const s2 = s1.charAt(0)+s1.charAt(5);
 const n1 = "Achmad Choiri";
 const n2 = n1.charAt(0).toUpperCase() + n1.charAt(6) + n1.charAt(12).toUpperCase();
 
 console.log(`Initials of ${s1}: ${s2}`);
 console.log(`Initials of ${n1}: ${n2}`);
 ```
 **Output:**
 
 > Initials of John Doe: JD
 >
 > Initials of Achmad Choiri: AC

# EX01 Developing a Simple Webserver
## Date:28-09-2024

## AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"><centre></centre>
    <title>Laptop Configuration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }
        th {
            background-color: aqua;
            color: black;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        h1{
            text-align: center;
        }
        h2{
            text-align: center;
        }
    </style>
</head>
<body>
    <h1 style="align-items: center;">AANKARSH J 24013602</h1>
    <h2 style="align-items: center;">Laptop Configuration</h2>
    <table>
        <tr>
            <th>Component</th>
            <th>Specification</th>
        </tr>
        <tr>
            <td>brand</td>
            <td>lenovo</td>
        </tr>
        <tr>
            <td>model</td>
            <td>ThinkPad</td>
        </tr>
        <tr>
            <td>Processor</td>
            <td>Intel Core i5-1335U</td>
        </tr>
        <tr>
            <td>RAM</td>
            <td>16GB DDR4</td>
        </tr>
        <tr>
            <td>Storage</td>
            <td>512GB SSD</td>
        </tr>
        <tr>
            <td>Graphics</td>
            <td>NVIDIA GTX 1660 Ti</td>
        </tr>
        <tr>
            <td>Display</td>
            <td>15.6" FHD (1920x1080)</td>
        </tr>
        <tr>
            <td>Operating System</td>
            <td>Windows 11</td>
        </tr>
    </table>
</body>
</html>

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/81874bdd-c8b0-42f0-8fa0-c4f25ac18681)


## RESULT:
The program for implementing simple webserver is executed successfully.

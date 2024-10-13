# Activity-26-CSS-FLEX

Apply CSS Flexbox on 5 pages (e.g., product layout, employee cards, student profiles, etc.)

Name your repository CSS_FLEX

Add documentation in the README.md file of your repository

Submit the GitHub repository link

Deadline: December 5 2024



Create HTML & CSS Files:
Inside each folder, create an index.html file and a corresponding style.css file. You can run these commands for each folder:

touch product_layout/index.html product_layout/style.css
touch employee_cards/index.html employee_cards/style.css
touch student_profiles/index.html student_profiles/style.css
touch pricing_table/index.html pricing_table/style.css
touch testimonials/index.html testimonials/style.css






1. Product Layout (product_layout/index.html)

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Product Layout</title>
</head>
<body>
    <div class="product-container">
        <div class="product-card">Product 1</div>
        <div class="product-card">Product 2</div>
        <div class="product-card">Product 3</div>
    </div>
</body>
</html>



Corresponding CSS (product_layout/style.css)
.product-container {
    display: flex;
    justify-content: space-between;
    padding: 20px;
}

.product-card {
    flex: 1;
    margin: 10px;
    padding: 20px;
    background-color: #f0f0f0;
    text-align: center;
}








2. Employee Cards (employee_cards/index.html)

   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Employee Cards</title>
</head>
<body>
    <div class="employee-container">
        <div class="employee-card">Employee 1</div>
        <div class="employee-card">Employee 2</div>
        <div class="employee-card">Employee 3</div>
    </div>
</body>
</html>




Corresponding CSS (employee_cards/style.css)

.employee-container {
    display: flex;
    justify-content: space-around;
}

.employee-card {
    flex: 1;
    margin: 10px;
    padding: 20px;
    background-color: #c2e0c2;
    text-align: center;
}







3. Student Profiles (student_profiles/index.html)
   
   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Student Profiles</title>
</head>
<body>
    <div class="student-container">
        <div class="student-card">Student 1</div>
        <div class="student-card">Student 2</div>
        <div class="student-card">Student 3</div>
    </div>
</body>
</html>





Corresponding CSS (student_profiles/style.css)

.student-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.student-card {
    flex: 1 1 30%; /* Grow to fill space */
    margin: 10px;
    padding: 20px;
    background-color: #e0c2c2;
    text-align: center;
}





4. Pricing Table(pricing_table/index.html)
   
   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Pricing Table</title>
</head>
<body>
    <div class="pricing-container">
        <div class="pricing-card">Basic</div>
        <div class="pricing-card">Standard</div>
        <div class="pricing-card">Premium</div>
    </div>
</body>
</html>




Corresponding CSS (pricing_table/style.css)

.pricing-container {
    display: flex;
    justify-content: space-around;
}

.pricing-card {
    flex: 1;
    margin: 10px;
    padding: 20px;
    background-color: #c2d2e0;
    text-align: center;
}





5. Testimonials (testimonials/index.html)
   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Testimonials</title>
</head>
<body>
    <div class="testimonial-container">
        <div class="testimonial-card">Testimonial 1</div>
        <div class="testimonial-card">Testimonial 2</div>
        <div class="testimonial-card">Testimonial 3</div>
    </div>
</body>
</html>



Corresponding CSS (testimonials/style.css)

.testimonial-container {
    display: flex;
    justify-content: space-between;
}

.testimonial-card {
    flex: 1;
    margin: 10px;
    padding: 20px;
    background-color: #e0c2e0;
    text-align: center;
}





And the last

Open any of the index.html files in your browser to see the layouts.
Technologies Used
HTML
CSS
Flexbox

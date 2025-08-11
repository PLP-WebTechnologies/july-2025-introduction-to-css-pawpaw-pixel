<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CSS Box Model Example</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Welcome to My CSS Box Model Demo</h1>
  </header>

  <main>
    <section class="box model-example">
      <h2>Box Model Demonstration</h2>
      <p>This box has padding, a border, and margin applied. It shows how spacing works inside and outside the box.</p>
    </section>

    <section class="box another-box">
      <h2>Another Box</h2>
      <p>This box has different padding, border thickness, and margin to illustrate consistent spacing and layout.</p>
    </section>
  </main>

  <footer>
    <p>© 2025 CSS Box Model Demo</p>
  </footer>
</body>
</html>
/* Basic Reset */
* {
  box-sizing: border-box; /* Important for box model */
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f0f4f8;
  padding: 20px;
  color: #333;
}

/* Header Styling */
header {
  text-align: center;
  margin-bottom: 30px;
}

/* Box Styling */
.box {
  background-color: #fff;
  border: 3px solid #007acc;
  padding: 20px;
  margin-bottom: 25px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

/* Specific variations */
.model-example {
  padding: 30px;
  border-color: #ff6600;
  margin-bottom: 40px;
}

.another-box {
  padding: 15px;
  border-color: #009933;
  margin-bottom: 40px;
}

/* Footer Styling */
footer {
  text-align: center;
  font-size: 0.9rem;
  color: #666;
  margin-top: 40px;
}

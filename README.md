- <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Crowdfunding Platform</title>
  <link rel="stylesheet" href="styles3.css">
</head>
<body>
  
  <header>
    <h1 style="color:DodgerBlue";> Crowdfunding Platform</h1>
  </header>
  <main>
    <section id="project-form">
      <h2>Submit Your Project</h2>
      <form id="new-project-form">
        <input type="text" id="project-title" placeholder="Project Title" required>
        <textarea id="project-description" placeholder="Project Description" required></textarea>
        <input type="number" id="fund-goal" placeholder="Fundraising Goal ($)" required>
        <input type="text" id="backer-rewards" placeholder="Backer Rewards" required>
        <button type="submit">Submit Project</button>
      </form>
    </section>
    <section id="projects">
      <h2>Current Projects</h2>
      <ul id="project-list"></ul>
    </section>
  </main>
  <script src="script3.js"></script>
</body>
</html>

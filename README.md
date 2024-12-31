<div id="header" align ="center">



  ![text](https://github.com/giseleortiz/GiseleOrtiz/assets/144640915/4f7cad3a-2654-4174-844c-6b3fc1f88299)

<h1 align="center" >Hello Welcome to my GitHub  👋 </h1> 
</div>

  <canvas id="skillsChart" width="400" height="400"></canvas>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  const ctx = document.getElementById('skillsChart').getContext('2d');
  new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: ['JavaScript', 'HTML', 'CSS', 'React', 'Node.js'],
      datasets: [{
        data: [40, 25, 15, 10, 10],
        backgroundColor: ['#FFD700', '#FF6347', '#4682B4', '#32CD32', '#8A2BE2']
      }]
    },
    options: {
      responsive: true,
      plugins: {
        legend: {
          position: 'top',
        }
      }
    }
  });
</script>


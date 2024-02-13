<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

<div class="container">
  <div>
    <h1 class="header_text">Yeeyy ! Finally </h1>
  </div>
  <div class="gif_container">
    <img
      src="https://gifsec.com/wp-content/uploads/2022/09/yes-gif-1.gif"
      alt="Cute animated illustration"
    />
  </div>
  <div>
    <h2 class="header_text">Let's Fix a Date</h2>
  </div>
  <!-- Insert the calendar code here -->

  <table id="calendar">
    <thead>
      <tr>
        <th>Sun</th>
        <th>Mon</th>
        <th>Tue</th>
        <th>Wed</th>
        <th>Thu</th>
        <th>Fri</th>
        <th>Sat</th>
      </tr>
    </thead>
    <tbody>
      <!-- Calendar content will be generated here using JavaScript -->
    </tbody>
  </table>

  <div id="savedDatesContainer"></div>

</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    var calendarBody = document.querySelector('#calendar tbody');

    generateCalendar(new Date());

    function generateCalendar(date) {
      var firstDay = new Date(date.getFullYear(), date.getMonth(), 1);
      var lastDay = new Date(date.getFullYear(), date.getMonth() + 1, 0);
      var currentDate = new Date(firstDay);

      // Clear existing content in the calendar body
      calendarBody.innerHTML = '';

      while (currentDate <= lastDay) {
        var row = document.createElement('tr');

        for (var i = 0; i < 7; i++) {
          var cell = document.createElement('td');

          if (currentDate.getMonth() === date.getMonth()) {
            cell.textContent = currentDate.getDate();
            cell.setAttribute('data-date', currentDate.toISOString().split('T')[0]);
            cell.addEventListener('click', function() {
              saveAndNavigateToNextPage(this.getAttribute('data-date'));
            });
          }

          row.appendChild(cell);
          currentDate.setDate(currentDate.getDate() + 1);
        }

        calendarBody.appendChild(row);
      }
    }

    function saveAndNavigateToNextPage(selectedDate) {
      saveToFileOnServer(selectedDate);

      // Navigate to the next page (you can customize the URL)
      window.location.href = 'nextpage.html';
    }

    function saveToFileOnServer(selectedDate) {
      // Fetch request to save the date on the server
      fetch('http://localhost:3000/saveToFile', {
        method: 'POST',
        headers: {
          'Content-Type': 'text/plain',
        },
        body: selectedDate,
      })
      .then(response => {
        if (!response.ok) {
          throw new Error('Error saving the date');
        }
      })
      .catch(error => {
        console.error('Error saving the date:', error);
      });
    }
  });
</script>

</body>
</html>

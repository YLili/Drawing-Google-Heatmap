# Drawing-Google-Heatmap
Drawing google heatmap using the data from Mysql database.
      You should change the HeatMap.jsp in the following position:
      (1) con = DriverManager.getConnection("jdbc:mysql://DatabaseIP/DatabaseName","UserName","Key");
      --------You should change the "DatabaseIP" with your Mysql's IP address(sometimes maybe localhost), change the "DatabaseName" with your database's name, change the "UserName" with your Mysql's username, change the "Key" with your Mysql's key.
      (2) src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=visualization&callback=initMap">
      --------You should change the "YOUR_API_KEY" with your API_KEY in Google.

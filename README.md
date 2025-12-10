📘 JMeter Load Testing on Pet Store Demo Web Application<br>
This repository contains the performance and load testing project executed on the Pet Store Demo Web Application using Apache JMeter.<br>
The goal of this project was to analyze how the application behaves under different user loads and measure its performance metrics across multiple critical pages.<br>

📌 Test Objective<br>
To evaluate the performance, stability, and responsiveness of the Pet Store demo website under varying user loads by executing multiple load test scenarios on key application pages.<br>

🧪 Test Scope<br>

A total of 9 web pages from the Pet Store application were tested:<br>
🏠 Home
👤 Sign In
📝 Sign Up
🛒 Cart
🐠 Fish Category
🐶 Dogs Category
🐱 Cats Category
🦎 Reptiles Category
🐦 Birds Category

🚀 Load Test Scenarios

Three separate load test runs were performed using different virtual user loads:<br>
1️⃣ Test Run – 100 Users<br>
Thread Group Users: 100<br>
Ramp-Up Period: 100 seconds<br>
Collected .jtl and .csv result files<br>
<img width="500" height="500" alt="image" src="PetStoreUser100/UI Image1.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser100/UI image2.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser100/Report1.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser100/Report2.JPG" />

2️⃣ Test Run – 500 Users<br>
Thread Group Users: 500<br>
Ramp-Up Period: 100 seconds<br>
Collected .jtl and .csv result files <br>
<img width="500" height="500" alt="image" src="PetStoreUser1000_100s/UI image1.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser1000_100s/UI image2.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser1000_100s/Report1.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser1000_100s/Report2.JPG" />

3️⃣ Test Run – 1000 Users<br>
Thread Group Users: 1000<br>
Ramp-Up Period: 100 seconds<br>
Collected .jtl and .csv result files <br>
<img width="500" height="500" alt="image" src="PetStoreUser500_100s/UI Image1.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser500_100s/UI Image2.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser500_100s/Report1.JPG" />
<img width="500" height="500" alt="image" src="PetStoreUser500_100s/Report2.JPG" />

📂 Repository Contents
This repository includes:
<ul>
<li>JMeter Test Plan (.jmx)</li>
<li>Raw test result files: .jtl files, .csv files </li>
<li>HTML report screenshots</li>
<li>Response times</li>
<li>Throughput graphs</li>
<li>Summary reports</li>
<li>Transaction performance</li>
<li>Documentation files</li>
<li>README.md</li>
</ul>

📊 Performance Metrics Observed

The following performance indicators were captured:
<ul>
  <li>⏱ Average Response Time</li>
  <li>⚡ Throughput (Requests/sec)</li>
  <li>📈 95th & 99th Percentile Response Time</li>
  <li>📉 Error Percentage</li>
  <li>🔁 Transaction Success/Failure Rate</li>
  <li>🕒 Server Response Distribution</li>
</ul>

🛠 Tools & Technologies Used
<ul>
  <li>Apache JMeter 5.3</li>
  <li>Java</li>
  <li>CSV/JTL Result Parsing</li>
  <li>GitHub for version control</li>
  <li>HTML Report Dashboard</li>
</ul>

▶️ How to Run the Test

=>  Install Apache JMeter<br>
=>  Clone this repository:  git clone https://github.com/your-username/your-repo-name.git<br>
=>  Open JMeter → Load the .jmx test plan<br>
=>  Modify Thread Group (optional)<br>

**  Run tests in GUI or Non-GUI mode:<br>
=>  jmeter -n -t TestPlan.jmx -l results.jtl<br>

**  Generate HTML Report:<br>
=>  jmeter -g results.jtl -o HTMLReport<br>

🎯 Conclusion

This load-testing project demonstrates how the Pet Store application performs under gradual user load increments from 100 → 500 → 1000 users.<br>
All raw data, reports, and screenshots are available in this repository for analysis and future reference.
  

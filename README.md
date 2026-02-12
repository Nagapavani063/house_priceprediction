<h1>🏠 House Price Prediction Project Documentation</h1>

<section>
<h2>1. Abstract</h2>
<p>
The House Price Prediction system is developed using Machine Learning techniques 
to estimate residential property prices. The project analyzes historical housing data 
and builds a regression-based predictive model. The trained model is evaluated using 
standard loss functions and deployed using Flask to provide real-time predictions.
</p>
</section>

<section>
<h2>2. Introduction</h2>
<p>
House prices depend on multiple factors such as size, location, number of rooms,
construction year, and amenities. Manual estimation is often inaccurate.
Machine Learning provides a data-driven approach to predict prices efficiently.
</p>
</section>

<section>
<h2>3. Problem Statement</h2>
<p>
Traditional pricing methods rely on manual estimation and fixed rules.
There is a need for an automated system that analyzes structured housing data 
and predicts prices accurately using statistical learning techniques.
</p>
</section>

<section>
<h2>4. Objectives</h2>
<ul>
<li>Analyze housing dataset</li>
<li>Preprocess and clean data</li>
<li>Train regression model</li>
<li>Evaluate performance using loss functions</li>
<li>Deploy using Flask</li>
</ul>
</section>

<section>
<h2>5. Scope of the Project</h2>
<p>
The project focuses on structured housing data and regression-based prediction.
It includes model training, evaluation, and web deployment.
Future enhancements can include advanced ML models and real-time data integration.
</p>
</section>

<section>
<h2>6. Technologies and Libraries Used</h2>
<ul>
<li>Python</li>
<li>Pandas & NumPy</li>
<li>Scikit-learn</li>
<li>Matplotlib & Seaborn</li>
<li>Flask</li>
<li>HTML & CSS</li>
</ul>
</section>

<section>
<h2>7. System Design (OOP Architecture)</h2>

<h3>1.DataHandler Class</h3>
<p>Handles dataset loading and preprocessing.</p>

<h3>2.ModelTrainer Class</h3>
<p>Trains, evaluates, and saves the model.</p>

<h3>3.HousePricePredictor Class</h3>
<p>Loads trained model and predicts house prices.</p>

<h3>4.WebApp Class</h3>
<p>Handles Flask routing and user interaction.</p>

</section>

<section>
<h2>8. Dataset Description</h2>
<p>
Structured CSV dataset containing features like bedrooms, bathrooms,
area, floors, year built, city, country, and sale date.
</p>
<p><strong>Target Variable:</strong> Price</p>
</section>

<section>
<h2>9. Methodology</h2>

<h3>Linear Regression Formula</h3>
<div class="formula">
y = β0 + β1x1 + β2x2 + ... + βnxn
</div>

<p>
Where y is predicted price, β0 is intercept, and β1...βn are coefficients.
</p>

<h3>Train-Test Split</h3>
<p>80% data used for training, 20% used for testing.</p>

</section>

<section>
<h2>10. Architecture</h2>
<p>
User → Web Interface → Flask Backend → ML Model → Prediction Output
</p>
</section>

<section>
<h2>11. Implementation</h2>
<ul>
<li>Data preprocessing</li>
<li>Model training</li>
<li>Model evaluation</li>
<li>Model saving using pickle</li>
<li>Flask integration</li>
</ul>
</section>

<section>
<h2>12. Results and Analysis</h2>

<h3>1.Mean Squared Error (MSE)</h3>
<div class="formula">
MSE = (1/n) Σ (yi - ŷi)²
</div>

<h3>2.Root Mean Squared Error (RMSE)</h3>
<div class="formula">
RMSE = √((1/n) Σ (yi - ŷi)²)
</div>

<h3>3.Mean Absolute Error (MAE)</h3>
<div class="formula">
MAE = (1/n) Σ |yi - ŷi|
</div>

<h3>4.R² Score</h3>
<div class="formula">
R² = 1 - [ Σ(yi - ŷi)² / Σ(yi - ȳ)² ]
</div>

<table>
<tr>
<th>Metric</th>
<th>Training</th>
<th>Testing</th>
</tr>
<tr>
<td>R² Score</td>
<td>≈ 88%</td>
<td>≈ 84%</td>
</tr>
<tr>
<td>MSE</td>
<td>Low</td>
<td>Slightly Higher</td>
</tr>
</table>

</section>

<section>
<h2>13. Applications</h2>
<ul>
<li>Real Estate Market Analysis</li>
<li>Property Buying & Selling</li>
<li>Bank Loan Evaluation</li>
<li>Urban Planning</li>
<li>Online Property Platforms</li>
</ul>
</section>

<section>
<h2>14. Advantages</h2>
<ul>
<li>Accurate and data-driven predictions</li>
<li>Reduces manual estimation errors</li>
<li>Real-time prediction capability</li>
<li>Scalable and extendable system</li>
</ul>
</section>

<section>
<h2>15. Limitations</h2>
<ul>
<li>Assumes linear relationship</li>
<li>Limited dataset features</li>
<li>No real-time market data</li>
<li>Manual retraining required</li>
</ul>
</section>

<section>
<h2>16. Future Enhancements</h2>
<ul>
<li>Random Forest, XGBoost implementation</li>
<li>Deep Learning models</li>
<li>Cloud deployment</li>
<li>Real-time API integration</li>
<li>Automated retraining pipeline</li>
</ul>
</section>

<section>
<h2>17. Conclusion</h2>
<p>
The House Price Prediction system successfully demonstrates the practical 
implementation of Machine Learning for real-world real estate problems.
The model achieves strong predictive performance and is deployed using Flask 
for user-friendly interaction.
</p>
</section>

<section>
<h2>18. References</h2>
<ul>
<li>Hands-On Machine Learning – Aurélien Géron</li>
<li>Pattern Recognition and Machine Learning – C. Bishop</li>
<li>Scikit-Learn Documentation</li>
<li>Flask Official Documentation</li>
</ul>
</section>

<footer>
J. Nagapavani | House Price Prediction Project
</footer>

</body>
</html>

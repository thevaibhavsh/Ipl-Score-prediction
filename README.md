# Ipl-Score-prediction

In the modern era of cricket analytics, where each run and decision can change the outcome, the application of Deep Learning for IPL score prediction stands at the forefront of innovation. This article explores the cutting-edge use of advanced algorithms to forecast IPL score in live matches with unprecedented accuracy. Exploring the analysis of historical data, player statistics, and real-time match conditions, discover how these predictive models are reshaping strategic insights and elevating the excitement of cricket analytics. Whether you’re a cricket aficionado or a data science enthusiast, uncover how this technology is revolutionizing the game’s predictive capabilities and strategic planning.
We humans can’t easily identify patterns from huge data, and thus here, machine learning and IPL score prediction using deep learning come into play. These advanced techniques learn from how players and teams have performed against each other in the past, training models to predict outcomes more accurately. While traditional machine learning algorithms provide moderate accuracy, IPL Score In live prediction benefits greatly from deep learning models that consider various attributes to deliver more precise results.

# IPL Score Prediction Model

This project demonstrates an IPL score prediction model using deep learning. The model predicts the total score based on features like the venue, batting team, bowling team, striker, and bowler.

## Requirements

To run this project, you'll need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `keras`
- `tensorflow`
- `ipywidgets`

## Project Structure

1. **Data Preprocessing**
   - Load IPL dataset.
   - Drop unnecessary columns.
   - Encode categorical features.
   - Split data into training and testing sets.
   - Scale data for neural network input.

2. **Model Building**
   - Build a deep neural network using `keras.Sequential`.
   - Use a `Huber` loss function and `Adam` optimizer.
   - Train the model with `train_test_split` data.

3. **Evaluation**
   - Visualize model loss over epochs.
   - Calculate Mean Absolute Error (MAE) and Mean Squared Error (MSE) on test data.

4. **Interactive Score Prediction**
   - Use `ipywidgets` to create an interactive form for user inputs.
   - Make predictions based on selected venue, teams, striker, and bowler.

## Output:
<img width="276" alt="image" src="https://github.com/user-attachments/assets/b7bcb829-2864-4c1d-bd05-615855ba20cb">

     

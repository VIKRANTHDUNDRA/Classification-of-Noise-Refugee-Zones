# Classification-of-Noise-Refugee-Zones
For the NOISE Project, I developed a machine learning model to classify noise refuge areas using noise levels, locations, and user-reported mood. Using Logistic Regression, SVM, Decision Trees, and a Regularized Decision Tree, I achieved 89.24% accuracy. This showcases my expertise in classification algorithms and model evaluation.

# Introduction:

The NOISE Project, funded by the National Science Foundation, aims to investigate the impact of noise pollution on personal and community well-being, with a focus on historically marginalized communities. As part of this initiative, we are tasked with classifying areas as noise refuges or not, utilizing data collected through the NOISE Project mobile app.

# Problem Statement:

Noise pollution poses significant health risks, including permanent hearing loss and various other health hazards. Identifying noise refuge areas, where individuals can escape excessive noise exposure, is crucial for promoting community well-being and environmental justice. However, determining these areas manually is time-consuming and inefficient.

# Objective:

The primary objective of this project is to develop a machine learning model capable of classifying areas as noise refuges or not based on data collected through the NOISE Project mobile app. By automating this process, we aim to provide communities with actionable insights to mitigate the adverse effects of noise pollution and promote healthier sound environments.

# Data:
# Link to Dataset: https://noiseproject.org/data-download/

# Here's a brief summary of each variable in the dataset:

1. Start date/time in UTC:This variable represents the date and time (in Coordinated Universal Time) when the noise observation began. It follows the format yyyy-MM-dd HH:mm:ss (24-hour time).
2. Timezone: Indicates the timezone where the observation was taken, providing context for converting the start date/time to the observer's local time.
3. Duration (s): Represents the duration of the noise observation in seconds. The standard duration is 29 seconds according to the NOISE Project protocol.
4. Observer ID: An anonymous numeric ID representing a user installation of the NOISE Project mobile app.
5. Latitude: North-south coordinate with 5 decimal places of precision, indicating the location where the measurement took place. Latitude is detected through the GPS interface of the mobile device.
6. Longitude: East-west coordinate with 5 decimal places of precision, indicating the location where the measurement took place. Longitude is detected through the GPS interface of the mobile device.
7. Mean volume (dBA): Arithmetical mean (average) of the volume in A-weighted decibels (dBA) across the points sampled for the duration of the measurement. It represents the noise level recorded during the observation.
8. Mood: The user's self-reported mood during the observation, chosen from five emoji options ranging from very happy to very unhappy.
9. Could control noise exposure:  User's response to whether they could control their exposure to the noise, indicated as TRUE or FALSE.
10. Indoors: Indicates whether the observation took place indoors (TRUE) or outdoors (FALSE), based on the user's selection.
11. Emoji: Set of emoji chosen by the user to describe the setting of the noise observation.
12. Emoji descriptions: Unicode names for the selected emoji, provided for information purposes.
13. Nominated as noise refuge: Indicates whether the user suggested the observed location as a 'noise refuge' (TRUE) or not (FALSE) at the conclusion of the observation.


# Scope:

1.	Utilize the NOISE Project dataset, consisting of noise observations including time, location, decibel levels, and observer mood.
2.	Implement machine learning algorithms to classify areas as noise refuges or not.
3.	Evaluate the performance of the classification model using appropriate metrics.
4.	Provide recommendations for identifying and designating noise refuge areas based on model predictions.

# Constraints:

1.	Limited availability of labeled data for model training.
2.	Variability in noise levels and environmental factors across different locations and times.
3.	Ethical considerations regarding data privacy and community engagement.

# Significance:

This project addresses the pressing need to combat noise pollution and promote equitable access to safe and healthy sound environments. By leveraging machine learning techniques, we can empower communities to identify and protect noise refuge areas, ultimately enhancing overall well-being and environmental justice.

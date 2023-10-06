# Car-insurance-claims
Prediction of car insurance claims and whether they are passed or not
PROJECT IDEA NAME- INSURANCE DOMAIN

PREDICTIVE MODELING FOR INSURANCE CLAIM PROBABILITY BASED ON COMPREHENSIVE CAR POLICY FEATURES AND SAFETY RATINGS

**BUSINESS PROBLEM STATEMENT**
Develop a predictive model that assesses the claim probability for car insurance policies. The objective would be to understand the factors that influence claim frequency and severity in the period of six months and enable insurance companies to better assess risk and determine appropriate premiums for policyholders.

1.	policy_id: The unique identifier for each insurance policy.

2.	policy_tenure: The length of time (in years) that the policy has been active.

3.	age_of_car: The age of the insured car (in years) at the time the policy was taken.

4.	age_of_policyholder: The age of the policyholder (in years) at the time the policy was taken.

5.	area_cluster: A categorical variable representing the cluster or category to which the area of residence belongs.

6.	population_density: A measure of the population density of the area where the policyholder resides.

7.	Make:  The make or manufacturer of the insured car.

8.	segment: The segment or category to which the insured car belongs (e.g., compact, sedan, SUV).

9.	model: The specific model or variant of the insured car.

10.	fuel_type: The type of fuel used by the insured car (e.g., petrol, diesel, electric).

11.	max_torque: The maximum torque output of the car's engine.

12.	max_power: The maximum power output of the car's engine.

13.	engine_type: The type of engine used in the insured car (e.g., inline, V-type).

14.	airbags: The number of airbags installed in the car.

15.	is_esc: A binary variable indicating whether the car has an electronic stability control (ESC) system.

16.	is_adjustable_steering: A binary variable indicating whether the car has adjustable steering.

17.	is_tpms: A binary variable indicating whether the car has a tire pressure monitoring system (TPMS).

18.	is_parking_sensors: A binary variable indicating whether the car has parking sensors.

19.	is_parking_camera: A binary variable indicating whether the car has a parking camera.

20.	rear_brakes_type: The type of rear brakes used in the car.

21.	displacement: The engine displacement of the car (typically measured in liters or cubic centimeters).

22.	cylinder: The number of cylinders in the car's engine.

23.	transmission_type: The type of transmission used in the car (e.g., manual, automatic).

24.	gear_box: The number of gears in the car's gearbox.

25.	steering_type: The type of steering system used in the car.

26.	turning_radius: The minimum radius of the circular path that the car can make.

27.	length: The length of the car.

28.	width: The width of the car.

29.	height: The height of the car.

30.	gross_weight: The gross weight or total weight of the car.

31.	is_front_fog_lights: A binary variable indicating whether the car has front fog lights.

32.	is_rear_window_wiper: A binary variable indicating whether the car has a rear window wiper.

33.	is_rear_window_washer: A binary variable indicating whether the car has a rear window washer.

34.	is_rear_window_defogger: A binary variable indicating whether the car has a rear window defogger.

35.	is_brake_assist: A binary variable indicating whether the car has a brake assist system.

36.	is_power_door_locks: A binary variable indicating whether the car has power door locks.

37.	is_central_locking: A binary variable indicating whether the car has central locking.

38.	is_power_steering: A binary variable indicating whether the car has power steering.

39.	is_driver_seat_height_adjustable: A binary variable indicating whether the driver's seat height is adjustable.

40.	is_day_night_rear_view_mirror: A binary variable indicating whether the car has a day/night rearview mirror

41.	is_ecw: A binary variable indicating whether the car has an electronic crash warning (ECW) system. ECW systems use sensors and algorithms to detect potential collisions and provide warnings to the driver.

42.	is_speed_alert: A binary variable indicating whether the car has a speed alert system. Speed alert systems typically monitor the vehicle's speed and provide warnings or alerts to the driver when they exceed a predetermined speed limit.

43.	ncap_rating: The safety rating of the car according to the New Car Assessment Program (NCAP). NCAP is a government-backed program that evaluates and rates the safety performance of new car models in various crash tests and assessments. The rating is usually represented by a star system, with a higher number of stars indicating a better safety performance.

44.	is_claim: A binary variable indicating whether an insurance claim has been filed for the car policy. This variable determines whether an insurance event has occurred for a given policy, with a value of 1 indicating that a claim was filed and 0 indicating no claim was filed.


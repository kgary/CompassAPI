Database Dump Readme:  This dump contains total 21 pins from 4010 to 4030 and the initial schedule for every patient has been created.
This dump has valid PINs and activity instances for 4016, 4020, and 4021.

For all the remaining pins, the patient would always start from the 1st module.
Below are the collections included in the database:
	1.	activities: 
This collection contains different activities that we have in out protocol like Relaxation, WorryHeads etc.

	2.	activityInstances : 
This collection contains instance of different activities for different patients.

	3.	dailyDiarySituations: 
It consists of the data for daily diary activity.

	4.	domains: It is used to maintain domain of the app.

	5.	emotions: 
This collection has the mapping of which activity or activities needs to be shown according to emotion and its intensity based on current module/session.
	6.	faceItChallenges: 
It has different face it challenges.

	7.	logger: 
It is used for logging APP side events. 

	8.	makeBelieveSituationNames: 
It contains the name list which used in make believe situations.

	9.	makeBelieveSituations: 
This collection has different situations for make believe activity.

	10.	masterSchedule: 
This is a generic schedule which would serve as a top-level schedule based on the protocol.

	11.	patientSchedules : 
This contains the main schedule for each patient. 

	12.	patientScores: 
This contains running instance of schedule for each patient. 

	13.	patients: 
It contains details for patients.

	14.	rewards: 
It has the rewards achieved by patient so far.

	15.	standUpSituations: 
It contains different situations for stand-up activity.

	16.	swapSituations: 
It contains situation details for SWAP activity.

	17.	trials: 
It has details about different trials and patients associated with those trials. 

	18.	worryHeadsSituations: 
It contains different situations for Worry Head activity.


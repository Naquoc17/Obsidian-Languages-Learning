2025-01-21 16:01

Status: #child 

Tags: [[Frankfurt University of Applied Sciences]] [[Yolov11]]


# Tof-project

# 21.01.2025
- The distribution of labeled data (measure unit: images):
	- Train: 1929
		- Human: 348 ~18%
		- Undefined Object: 271 ~14%
		- Human & Undefined Object: 33
		- No Object: 1342
	- Valid: 524
		- Human: 255 ~48%
		- Undefined Object: 134
		- Human & Undefined Object: 68
		- No Object: 203
	- Test: 227
		- Human: 125 ~55%
		- Undefined Object: 72
		- Human & Undefined Object: 35
		- No Object: 115

- Solution: I changed the distribution of the data by adding more human-labeled images to the training dataset from the validation and test datasets in the following proportions: (human, undefined, no obj) = (0.26, 0.14, 0.6)

- The new distribution of the data:
	- Train: 1911
		- Human: 497
		- Undefined Object: 268
		- Human & Undefined Object: 
		- No Object: 1146
	- Valid: 546
		- Human: 142
		- Undefined Object: 76
		- Human & Undefined Object: 
		- No Object: 328
	- Test: 273
		- Human:70
		- Undefined Object: 39
		- Human & Undefined Object: 
		- No Object: 164


# 22.01.2025

- I found way to use Yolov11 for my dataset: https://www.youtube.com/watch?v=A1V8yYlGEkI
- There is a challenge right now: How to improve the accuracy of the model detection

# 23.01.2025
- After talking with Van, I just found out the way to improve model of detection:
	- Yolov11 segmentation
	- Data Augmentation
	- Attention

# 26.01.2025
- I will refine all image at first
- The main idea is: 
	- I will use the method of average matrix calculation for every 3 single square on a row
	- ![[Pasted image 20250126125818.png]]
	- I divide image into 3 layer: Red, Green, Blue
	- The refining program is running only on the same layer

- Mission: Detect the good distance for every single layer

# 09.02.2025
- I'm fknig exhausted :)
- ![[Pasted image 20250209181638.png]]
- The idea is I will print out the matrix of distance data
- After that, I will nomalize  again



# References
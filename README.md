# Exam_2420

## Part 1

1. ```sudo apt update```
2. ```sudo apt upgrade```

## Part 2

1. To replace eco with echo I used the command ```:%s/eco/echo/g```
2. To replace numbs with :digit: I used the command ```%s/numbs/:digit:/g```
3. To replace V with C I used the command ```$s/V/C/g```
4. To replace -eq 1 to -eq 0, I manually changed it by pressing ```i``` to insert and navigated to it to change it to 1.

![image](https://user-images.githubusercontent.com/97579029/206561369-983a17dc-9c9e-4737-8f7d-1680e7d73dfb.png)

## Part 3

![image](https://user-images.githubusercontent.com/97579029/206561712-d167b1d6-26fb-4a16-8d4c-cf2b1ec3db40.png)

 
1. ![image](https://user-images.githubusercontent.com/97579029/206562251-d939e573-afe2-4d87-92b7-c16e2b8cb761.png)
Searched for boot using /boot

 
2. ![image](https://user-images.githubusercontent.com/97579029/206562480-fff69932-339f-4a0a-ad84-6b1c64610a33.png)
Searched priority using /priority, warning is one of the options in the priority man page


3. ![image](https://user-images.githubusercontent.com/97579029/206563272-3c326ff7-ec70-4296-82de-37d5d2683b04.png)
Searched output using /output


4. ![image](https://user-images.githubusercontent.com/97579029/206562875-fa03441c-19cd-4478-b930-9a23de3a6061.png)
Searched json using /json and found json-pretty using n and shift + n

### The command

```journalctl --boot --priority=warning --output=json-pretty```

![image](https://user-images.githubusercontent.com/97579029/206563860-3102d534-f159-4cd0-8758-6c078ba69b2e.png)




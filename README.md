# :construction_worker: The TVDB File Renamer <img src="https://poa5qzspd7.execute-api.us-east-1.amazonaws.com/live/hypercounterimage/2ade966219a2499d8c1f687c6dd6e5b3/counter.png" />
A quick utility that helps you organize your **Media Library** by scraping **TheTVDB.com** website and renaming your files in a neat and clean fashion. It's **extremely helpful** for **Plex**, **Kodi** or other media servers if you know what I mean :wink: :wink:.

Also helps you with missing episodes (example given below). 
If you like my repo, I really hope you consider :star2:ing it.

If you want to see a video walkthrough of the utility in action, click below
- [The TVDB File Renamer : Video Walkthrough](https://youtu.be/U5Q9pm4S10c)
- [![The TVDB File Renamer : Video Walkthrough](http://img.youtube.com/vi/U5Q9pm4S10c/0.jpg)](https://www.youtube.com/watch?v=U5Q9pm4S10c "The TVDB File Renamer : Video Walkthrough")

## Reduces your effort to organize and correctly name your media files :-

![BeforeAfter](https://ubhits.s3.amazonaws.com/tvdb_renamer/BeforeAfter.png)

The example below is for **Darkwing Duck**, one of my favorite childhood cartoons :)

![Program](https://ubhits.s3.amazonaws.com/tvdb_renamer/Program.png)

And below is the **output** when you run the program

![Terminal](https://ubhits.s3.amazonaws.com/tvdb_renamer/Terminal.png)

- All files that were **found and matched**, are marked in **Green**.
- All files where the names were **not matched** are marked with **Red**. 

## Diagnosing and Correcting Mismatched Files

Using the output from the program, it becomes very easy to correct the filenames.
In the example below, if we search **"brainteasers"** from the unmatched file in the **program output**, we find that it's **S03E03**.

![Find](https://ubhits.s3.amazonaws.com/tvdb_renamer/Find.png)

The program was not able to find the file because on tvdb, there is an **"!"** at the end of the filename.

![Diagnose](https://ubhits.s3.amazonaws.com/tvdb_renamer/Diagnose.png)

To correct, I **added the missing "!" to my file** and rerun the program, and **"BOOM goes the DYNAMITE!!!"**

![Corrected](https://ubhits.s3.amazonaws.com/tvdb_renamer/Corrected.png)

## How to Use
- Find your TV Serial on the TheTVDB.com
- Copy and paste the URL into the Program
- Point the files_path to your media file directory
- Run the Program

I hope this helps you. Please consider :star2:ing my repo if it did. It would encourage me a lot to share more with the community :relaxed:

# HUGE DISCLAIMER
I cannot stress this enough to please backup your files before you run this program. It works, but because we are renaming files on your system, there can be a chance that you lose important data. Please please please backup your data before you even think of running this program. I've tried my best to take care any edge issues, but still don't guarantee 100% stability! I can say with 100% confidence that it's worked for me beautifully! If you find any issues, please feel free to log them here.

![TheTVDB](https://ubhits.s3.amazonaws.com/tvdb_renamer/TheTVDB.png)

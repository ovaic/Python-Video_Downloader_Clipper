# Python

Download the CSV file. (EXCEL Dataset file "train2.csv" for YouTube video links.)

Filter the LABEL (e.g. slapping) for which you want to Download all videos.

For filtering:

select all headings (Row #1 Colomn A-H) -> Click on Data Tab -> Click on Filter from Sort & Filter box -> Drop Down Arrows will be shown on each heading in Row #1 -> Click on LABEL Drop Down Arrow -> Write your Label Name (e.g. slapping) in Search -> Press Enter

COPY-PASTE all data for that Label in another EXCEL file and ADD its full PATH in the code (line #9 df = pd.read_csv(r'PATH\links.csv') 

RUN your Jupyter Notebook TERMINAL in the folder where you want to Download the videos.

Make another folder named "clipped" in it to store clipped videos. (REQUIRED)*

Now just RUN it.

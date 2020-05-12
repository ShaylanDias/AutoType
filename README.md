
# AutoType

This is a simple script which takes in a text file argument and reads the file line-by-line, typing it into the current in focus window on your machine (very useful for texting a friend song lyrics or a movie script line by line as a prank).  

1. Make sure you have a valid Python 3 install with pip package manager!
2. Install the dependencies of the script with `pip install -r requirements.txt`
3. Run the script with `python3 autotype.py <filepath>`. This will run the script typing out each word in the file on its own with a 3 second delay before starting.
   1. You can make the script go by line with the arg `--byline`, so `python3 autotype.py --byline <filepath>`.
   2. You can also increase the time delay with the arg `-t <int for desired delay in seconds>`, so `python3 autotype.py -t 5 <filepath>` for a five second delay.
4. There will be a 3 second delay for you to navigate to the window and text field you want to type in before it begins. If you want to change this time, simply edit the `time_delay` variable at the top of autotype.py
5. Watch the script work!

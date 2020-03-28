# Midterm Feedback

## Overall Score: 
48 / 50

Generally, you had all the right ideas. Remember to look for patterns in the code you're writing and consider a way to make that code more generic rather than duplicating it.  Nice work!


## Part 1: Creating a JSON Rules File
Comments - Nice work.  They all look great.  I'm not sure what you're going to do to pick between PaO2 and A-a Gradient, though.

## Part 2: Functions to evaluate rules
Comments - These all look great in general.  The one thing you miight notice, though, is that you're writing a lot of the kind of code over and over -- the range comparison.  When I suggested that you should be able to do this without writing quite as much code, I was suggesting that you could write a generic function that would do any range lookup given the configuration file, the value, and which section to look in.  (-1)

Your FiO2 section used the FiO2 ranges niicely, but then had to hardcode getting either the 'Pa02' or 'A-a gradient' value sets.  If you had restructured your JSON slightly, then this wouldn't have needed to have that informaiton either.  (-1)


## Part 3: Put it all together
Comments - Nice and simple.  A little hard to read all on one line of code, though!

## Part 4: Accessing and processing the patient file
Comments - Nice work.  If you'd used Pandas here, it would have saved some code since read_csv can take a URL as its input.
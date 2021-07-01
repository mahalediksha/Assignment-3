# Assignment-3

Code:


altitude=int(input ("Actual altitude of the plane:"))

required_altitude=1000

maximum_altitude=5000

if altitude < required_altitude:
  print ("Safe to land")
elif altitude > required_altitude and altitude < maximum_altitude:
  print ("Bring down to 1000 that's required altitude")
else:
  print ("Turn around")

Output:

Example 1: Actual altitude of the plane:5000
           Turn around
Example 2: Actual altitude of the plane:800
           Safe to land
Example 3: Actual altitude of the plane:3500
           Bring down to 1000 that's required altitude

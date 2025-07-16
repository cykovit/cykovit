 ```ruby
 class Cyko < Human
   def initialize
     @name = 'cykovit'
     @age = 26
     @education = [ 'UCSD', 'Erasmus Rotterdam' ]
     @hobbies = [ 'gaming', 'art', 'CTFs' ]
   end

   def current_location
     'Paris, FR'
   end

   def next_locations
     ['Nantes, FR', 'Utrecht, NL']
   end

   def currently
     {
       studying: [ 'blockchain analysis' ],
       reading: [ 'a bunch of EU policies no one actually cares about' ],
       tinkering: [ 'malware samples', 'mobile app development' ]
      }
   end
 end
 ```
<br>
<p align="center">
<a href="https://www.youtube.com/watch?v=OBkZDwcVKro" target="_blank">
   <img src="https://tryhackme-badges.s3.amazonaws.com/cykovit.png?update=6">
</a>
</p>

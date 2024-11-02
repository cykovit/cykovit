 ```ruby
 class Cyko < Human
   def initialize
     @name = 'cykovit'
     @age = 25
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
       reading: [ 'a bunch of UE policies no one actually cares about' ],
       tinkering: [ 'malware samples', 'mobile app development' ]
      }
   end
 end
 ```

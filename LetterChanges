def LetterChanges(str)

 arr = str.split(//)
 arr.each do |x|
   if x != " "
     x.succ!
     if ['a','e','i','o','u'].include? x.downcase
       x.capitalize!
     end
   end
 end
 
 return arr.join
        
end

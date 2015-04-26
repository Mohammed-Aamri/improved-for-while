# improved-for-while
bank account uisng loop
Puts “ please enter your user name”
Username=gets.downcase
Username=username.strip

Puts”do you want a new account”

Answer=gets.downcase
Answer=answer.strip

If answer==”yes”     # validation

 While answer==” yes” do

  Puts”how much you want to include”
  Money=gets.to_f   # money deposit
  Puts”your balance #[money] Omani “
  Puts ”you want other services” # other services
 end

Elseif answer== “no”
  Put “thanks you #[username]”  # bye message

Else
  Puts”error"
end




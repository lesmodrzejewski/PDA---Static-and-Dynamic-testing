### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:
  
  #the CardGame model properties are not defined ex. card, card2

  def check_for_ace(self, card):
    if card.value = 1: #one equal sign is missing
      return True
    else #there is not collon after else
      return False
   

  dif highest_card(self, card1 card2): #dif instead of def # there is no comma between the two parameters
  if card1.value > card2.value: #the if statement should be indented
    return card #1 is missing
  else:
    return card2
  


def cards_total(self, cards):
  total # a value should be assigned
  for card in cards:
    total += card.value
    return "You have a total of" + total #incorrect indentation


```
### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby
### Testing task 2 code:

# Carry out dynamic testing on the code below.
# Correct the errors below that you spotted in task 1.

require_relative('card.rb')
# NO ./ BEFORE FILE PATH
class CardGame

  #NO INITIALIZE METHOD

  def checkforAce(card)
    if card.value = 1
      # SINGLE (=) SHOULD BE DOUBLE ( == )
      return true
    else
      return false
    end
  end

  dif highest_card(card1 card2)
  # SHOULD BE DEF, NOT DIF
  # NO COMMA BETWEEN ARGUMENTS
  if card1.value > card2.value
    return card.name
  else
    card2
  # NO RETURN BEFORE card2
  end
end
end
# 2 ENDS, SHOULD BE 1

def self.cards_total(cards)
  total
  # TOTAL SHOULD BE SET TO SOMETHING, LIKE 'O'
  for card in cards
    total += card.value
    return "You have a total of" + total
    # TOTAL SHOULD BE INTERPOLATED INTO STRING, LIKE "You have a total of #{total}"
  end
end


```

import random as randint

class LivingThing():
    def __init__(self):
         self.name = name
         self.health = 15
         self.stamina = 100
    def tire(self):
        self.stamina = self.stamina - 100
    def damaged(self):
        self.health = self.health - 1
    def heal(self):
        self.health = self.health + 10
    
class Player(LivingThing):
    self.name = name
    self.health = 100
    self.stamina = 100
     def help(self):
         for in Commands.keys get keys
         print('Your Command Options are:')
         print(keys)
    
    def fight(self):
         print('You had a clashing on with ', monster.name , 'and as a result you lost', self.health = self.health - randint(1,10))
         print('Your health is now: ', self.health)
    def explore(self):
         print('Life is filled with Wonder, You go Exploring, from the plainest of lands to the vastest valleys filled with the darkest caves, deepest lakes!')
         randint(1,2) 2 = print('You are faced by', monster.name), 1 = print('you narrowly dodged facing ', monster.name )
    def run(self):
         print('you ran way from ', monster.name, 'and as a result, you lost ' self.stamina = self.stamina - randint(1,10), 'stamina!')


Class Monster(LivingThing):
   self.name = name
   self.health = health
   self.stamina = 100
  

Goblin=Monster('Goblin',15)
Dragon=Monster('Dragon',18)
Monsters=[Goblin,Dragon]
Dragon.append
Goblin.append

choice = random.randint(Monsters)

print('choose your command!)
name = input('What is your name? ')
hero = Player
hero.name = input

Commands = {
    'help' Player.help,
    'run': Player.run,
    'explore': Player.explore,
    'fight': Player.fight,
}

if Player.health == 0:
    print('looks like you died. the end..)
elif Monster.health == 0:
    print(monster.name, 'Died')
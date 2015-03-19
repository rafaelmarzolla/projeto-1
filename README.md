# projeto-1
from random import choice

player_wins=0
comp_wins=0

lista = ["pedra", "papel", "tesoura", "lagarto", "spock"]
print("Vamos jogar uma partida de pedra-papel-tesoura-lagarto-Spock?\n")

while player_wins<3 or comp_wins<3:
    
    jc = choice(lista) #jogada do computador
    jp = input("Faca seu movimento\n")  #jogada do player
    
    if jc== "pedra" and jp== "tesoura":
       print("comp_wins") 
       comp_wins=comp_wins+1  
       player_wins=0
    if jc== "pedra" and jp=="lagarto":   
       print("comp_wins") 
       comp_wins=comp_wins+1  
       player_wins=0
    if jc=="pedra" and jp== "papel" :
       print("player_wins")
       comp_wins=0
       player_wins=player_wins+1
    if jc=="pedra" and jp== "spock"  :
       print("player_wins")
       comp_wins=0
       player_wins=player_wins+1
    if jc=="papel" and jp=="pedra" :
       print("comp_wins")
       comp_wins+=1 
       player_wins=0
    if jc=="papel" and jp=="spock"  :
       print("comp_wins")
       comp_wins+=1 
       player_wins=0
    if jc=="papel" and jp=="tesoura" :
       print("player_wins")
       comp_wins=0
       player_wins+=1
    if jc=="papel" and jp=="lagarto":  
       print("player_wins")
       comp_wins=0
       player_wins+=1 
    if jc=="tesoura" and jp=="papel" :
       print("comp_wins")
       comp_wins+=1
       player_wins=0
    if jc=="tesoura" and jp=="lagarto":
       print("comp_wins")
       comp_wins+=1
       player_wins=0
    if jc=="tesoura" and jp=="pedra" :
       print("player_wins")
       comp_wins=0
       player_wins+=1
    if jc=="tesoura" and jp=="spock":  
       print("player_wins")
       comp_wins=0
       player_wins+=1
    if jc=="lagarto" and jp=="spock" :
       print("comp_wins") 
       comp_wins+=1
       player_wins=0
    if jc=="lagarto" and jp=="papel":  
       print("comp_wins") 
       comp_wins+=1
       player_wins=0 
    if jc=="lagarto" and jp=="pedra" :
       print("player_wins")
       comp_wins=0
       player_wins+=1
    if jc=="lagarto" and jp=="tesoura":
       print("player_wins")
       comp_wins=0
       player_wins+=1 
    if jc=="spock" and jp=="tesoura" :
       print("comp_wins")
       comp_wins+=1
       player_wins=0
    if jc=="spock" and jp=="pedra":
       print("comp_wins")
       comp_wins+=1
       player_wins=0  
    if jc=="spock" and jp=="papel" :
       print("player_wins")
       comp_wins=0
       player_wins+=1
    if jc=="spock" and jp=="lagarto":  
       print("player_wins")
       comp_wins=0
       player_wins+=1 
    if jc==jp:
       print("empate")           
       comp_wins=0
       player_wins=0
    if player_wins == 3 
       print("voce ganhou")
    if comp_wins == 3:
       print("o pc ganhou")
        

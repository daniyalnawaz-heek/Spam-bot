# Spam-bot
A simple spam bot to annoy anyone.


#importing pyautogui and time module
import pyautogui
import time

#setting timer
time.sleep(1)

#opening the file to read the spam text
file = open("spam.txt","r")

#iterating to print every word in the file
for word in file:

  #typing the word in the input bar of whatsapp
  pyautogui.typewrite(word)

  #when pressed enter the spam starts
  pyautogui.press("enter")
  

  




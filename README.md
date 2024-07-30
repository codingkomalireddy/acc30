#ceasercyber code
text='danger'
i=0
while i<len(text):
    letter=text[i]
    print(chr(ord(letter)+1),end='')
    i+=1

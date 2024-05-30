def ceaser_encrypt(plaintext,n):
    ans = ""
    for i in range(len(plaintext)):
        ch = plaintext[i]
        #adding space
        if ch==" ":
            ans+=" "
        # encryption for uppercase 
        elif (ch.isupper()):
            ans += chr((ord(ch) + n-65) % 26 + 65)
        # encryption for lowercase 
        else:
            ans += chr((ord(ch) + n-97) % 26 + 97)
    return ans
plaintext = input()
n = int(input())
print("Plain Text is : " + plaintext)
print("Shift pattern is : " + str(n))
print("Cipher Text is : " + ceaser_encrypt(plaintext,n))

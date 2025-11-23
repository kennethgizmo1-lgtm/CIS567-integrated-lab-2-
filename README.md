# CIS567-integrated-lab-2-
Week 7 Assignment - GitHub Lab Repository 2
text = input().split()
char = text[0]
phrase = " ".join(text[1:])

count = phrase.count(char)

if count == 1:
    print(f"{count} {char}")
else:
    print(f"{count} {char}'s")

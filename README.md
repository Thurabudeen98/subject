# anagram
str1=input("string1:")
str2=input("string2:")
sorted_str1=sorted(str1)
sorted_str2=sorted(str2)
if len(str1)==len(str2):
  if sorted_str1==sorted_str2:
    print("The given strings are anagram")
  else:
    print("The given strings are not anagram")

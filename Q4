Input: digits = "23"
Output: ["ad","ae","af","bd","be","bf","cd","ce","cf"]
Example 2:
 
Input: digits = ""
Output: []
Example 3:
 
Input: digits = "2"
Output: ["a","b","c"]E


n=input()
d={"2":"abc","3":"def","4":"ghi","5":"jkl","6":"mno","7":"pqrs","8":"tuv","9":"wxyz"}
if n=="":
    print("[]")
else:
    
    r=[""]
    for i in n:
        new_r=[]
        for j in r:
            for ch in d[i]:
                new_r.append(j+ch)
        r=new_r
    print(r)



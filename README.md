# Challenge-Questions day 1
print("-------Grade Card--------")
sub1=int(input("enter marks of subject 1:"))
sub2=int(input("enter marks of subject 2:"))
sub3=int(input("enter marks of subject 3:"))
sub4=int(input("enter marks of subject 4:"))
sub5=int(input("enter marks of subject 5:"))
total_marks=sub1+sub2+sub3+sub4+sub5
print("Total marks gained= ",total_marks)
percentage=(total_marks/500)*100
print("Percentage= ",percentage,"%")
if percentage>=90:
    print("Grade=A+")
elif percentage<90 and percentage>=80:
    print("Grade=A")
elif percentage<80 and percentage>=70:
    print("Grade=B")
elif percentage<70 and percentage>=60:
    print("Grade=C")
elif percentage<60 and percentage>=50:
    print("Grade=D")
else:
    print("Grade=F")



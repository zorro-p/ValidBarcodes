# ValidBarcodes
Checks the last number which is check digit is correct or not
</br>
Input can be of any forms removes everything except digits (but not preppended extra zeros) 
</br>
Source(short code for Damm,Verhoeff using Codegolf and Group theory)
</br>
EPA13(weighting of elements and mod 10 based so if 2-digits are jumbled say ab becomes ba using 31 system)
</br>
error will be due to change in weight(3*(a)+b)-(a+3*(b))=2*(a-b) ==0mod10
</br>
a-b==0mod10 gives 5 pairs (0,5) (1,6) (2,7) (3,8) (4,9)
</br>
so error percentage using combinations of 2 =>(5X2)/(10X10)=10/100 out of 90/100

</br>TimeComplexity for Epa13:O(n)

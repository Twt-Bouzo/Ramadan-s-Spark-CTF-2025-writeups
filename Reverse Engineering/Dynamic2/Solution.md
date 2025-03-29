![image](https://github.com/user-attachments/assets/38ca7448-d2bc-45ab-b485-41b01396e25c)


I reused the functions from the first task, Dynamic1, with some modifications.

I added atb() function : atbaash cipher

![image](https://github.com/user-attachments/assets/54e6e8e0-6c48-4a9b-b7d9-75400173b909)

atb function : return reverse(resultat)

so we get _v3r_c1m4nyD{krapS

iaj_l2amo() :


I added srandom , So X=2  abs and  power function .

SO :

i=1 --->res=abs(0-power(x,1)=2 

i=2 --->res = abs(0-power(x,2))=4+res=42

i=3 --->res = abs(1-power(x,3))=7+res=742

i=4 --->res = abs(1-power(x,4))=15+res=15742

i=5 --->res = abs(2-power(x,5))=30+res=3015742

i=6 --->res = abs(4-power(x,6))=60+res=3015742

i=7 --->res = abs(7-power(x,77))=121+res=1213015742

i=8 --->res = abs(13-power(x,8))=243+res=1213015742

i=9 --->res = abs(24-power(x,9))=488+res=4881213015742

return res


I added srandom on test function

In fact, test : return power(x,CountWays(4)) = retrun power(2,5)=32

![image](https://github.com/user-attachments/assets/45d60907-10e5-4bb1-9ae2-f0f211aa116c)

Flag : Spark{Dyn4m1c_r3v_48824312160301574232}


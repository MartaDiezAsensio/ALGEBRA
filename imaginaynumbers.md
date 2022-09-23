# Imaginary numbers


### Basic Complex operations

When operating with complex numbers we will proceed as we do with regular polynomials with the only peculiarity that when we encounter a $j^2$ we will substitude this expression by the number $-1$. 

1- Sum / Substraction 


  - $(a + jb) + (c + jd) = a+c + j(b + d)$


2- Multiplication / Divisioin

  - $(a+jb)*(c+jd) = ac + jad + jbc + j^2bd = ac + jad + jbc -bd = ac - bd + j(ad + bc)$

### Binomial form of complex numbers

To express a complex number in the binomial form we need to divide the imaginary exponent by two and do the following: 

**Given the number $j^{255}$**

1- we divide $255$ by $2$  $(225/2 = 127 (reminder=1))$.

2- Once we have the result we can rewrite the complex number as $(j^{2})^{127} + j^1$.

3- Finally we continue doing this procedure until we get to the minimum exponent.

 - $(j^{2})^{127} + j^1 = (j^{2})^{63} + j^1 = (j^{2})^{31} + j^1 = (j^{2})^{15} + j^1 = (j^{2})^{7} + j^1 = (j^{2})^{3} + j^1 $




**Given the expression $\frac{e^{-3+5j}-e^{-3-5j}}{e^{-3-5j}+e^{-3+5j}}$**

1- we must know Euler's formula:

> $e^{jx}=cos x + j sin x$

A proof of this formula is:

>> We can rearrange the formula as $1 = \frac{e^{i\theta}}{\cos{(\theta)} + i \sin{(\theta)}}$


>> Then $0 = \frac{d}{d\theta}\left(\frac{e^{i\theta}}{\cos{(\theta)} + i\sin{(\theta)}}\right).....\text{[Taking der. of both sides]}$


>> $0 = \frac{ie^{i\theta}\cos{(\theta)} - e^{i\theta}\sin{(\theta)} + e^{i\theta}\sin{(\theta)} - ie^{i\theta}\cos{(\theta)}}{\cos^{2}{(\theta)} + 2 i \cos{(\theta)}\sin{(\theta)} - \sin^{2}{(\theta)}}$


>> $0 = \frac{0}{\cos^{2}{(\theta)} + 2 i \cos{(\theta)}\sin{(\theta)} - \sin^{2}{(\theta)}}$


>> $0 = 0$


> $L.H.S = R.H.S $


2- Now we use Euler's formula to solve:

   - $\frac{e^{-3+5j}-e^{-3-5j}}{e^{-3-5j}+e^{-3+5j}} = \frac{e^{-3}(2jsin5)}{e^3(2cos5)} = e^{-6}jtg5$



### Calculate complex roots

Lets put the case you need to calculate the sixth roots of **-8**.

The steps you need to follow in order to do so are:

1. Convert the complex number ( -8 + 0j) into polar form. 
    - $|-8 + 0j| = \sqrt{64 + 0} = 8$ 
    - $tan \alpha = \frac{0}{-8} = 0$ 
    - With these information we make a graphical representation of the complex number and we deduct that the argument is $\pi$. 


2. Now we calculate the 6 roots.
- $\sqrt[6]{-8}= (8e^{j\pi})^{\frac{1}{6}} = 8{\frac{1}{6}}e^{j \frac{\pi + 2k\pi}{6}} = 2{\frac{3}{6}}e^{j \frac{\pi + 2k\pi}{6}} = 2{\frac{1}{2}}e^{j \frac{\pi + 2k\pi}{6}} = $   


-  *These are the roots:*



1- $2{\frac{1}{2}}e^{j \frac{\pi}{6}} = \sqrt{2}(cos\frac{\pi}{6} + jsin\frac{\pi}{6}) = \sqrt{2}(\frac{1}{2} + j\frac{\sqrt{3}}{2}) = \frac{\sqrt{2}}{2} + j \frac{\sqrt{6}}{2}$

 

2- $2{\frac{1}{2}}e^{j \frac{3\pi}{6}} = \sqrt{2}_{\frac{\pi}{2}} = \sqrt{2}(cos\frac{\pi}{2} + jsin\frac{\pi}{2}) = \sqrt{2}(0 + j) = j\sqrt{2}$



3- $2{\frac{1}{2}}e^{j \frac{5\pi}{6}} = \sqrt{2}(cos\frac{5\pi}{6} + jsin\frac{5\pi}{6}) = \sqrt{2}(-\frac{1}{2} + j\frac{\sqrt{3}}{2}) = -\frac{\sqrt{2}}{2} + j \frac{\sqrt{6}}{2}$

  

4- $2{\frac{1}{2}}e^{j \frac{7\pi}{6}} = \sqrt{2}(cos\frac{7\pi}{6} + jsin\frac{7\pi}{6}) = \sqrt{2}(-\frac{1}{2} - j\frac{\sqrt{3}}{2}) = -\frac{\sqrt{2}}{2} - j \frac{\sqrt{6}}{2}$

     
      
5- $2{\frac{1}{2}}e^{j \frac{9\pi}{6}} = \sqrt{2}_{\frac{3\pi}{2}} = \sqrt{2}(cos\frac{3\pi}{2} + jsin\frac{3\pi}{2}) = \sqrt{2}(0 + j(-1)) = -j\sqrt{2}$
      
        
6- $2{\frac{1}{2}}e^{j \frac{11\pi}{6}} = \sqrt{2}(cos\frac{11\pi}{6} + jsin\frac{11\pi}{6}) = \sqrt{2}(\frac{1}{2} - j\frac{\sqrt{3}}{2}) = \frac{\sqrt{2}}{2} - j \frac{\sqrt{6}}{2}$













> Dorothy told me this

 

- line 1

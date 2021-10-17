# Class-for-investment
The class Investment helps to get the value of investment based on the value of principal and rate after two years
class Investment:
  def __init__(self,p,r):
    self.p= p
    self.r = r
  def value_after(self):
    return self.p*((1+self.r)**2)
    
    
i = Investment (1000,5) 
print(i.value_after())

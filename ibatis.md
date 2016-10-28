#ibatis record

1.sharp should close the character
  - `EXPENDITRUE_TYPE = #EXPENDITRUE_TYPE:VARCHAR #` is wrong
  - `EXPENDITRUE_TYPE = #EXPENDITRUE_TYPE:VARCHAR#` is true
  
  i had writed it as the wrong method to use the `Inject Language` in IntelliJ IDEA.but it did not  distinguish the VARCHAR when the parameter is `null`

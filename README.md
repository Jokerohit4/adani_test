# adani_test


void main() {
  var nums = [1,0,2,0,2,2,2,1,1,0];
 print(sort(nums));//print array
  }
  
//sort
sort(var nums){
  var numZero = <int> [];
  var numOne = <int> [];
  var numTwo= <int> [];
  for(int i=0;i<nums.length;i++)
  {
    if(nums[i]==0)
    {
      numZero.add(0);//adding an element into list of zeroes
    }
    else if(nums[i]==1)
    { 
      numOne.add(1);// adding  an element into another list of ones
    }
    else
    {
     numTwo.add(2); // adding  an element into another list of two
    } 
  }
  return numZero+numOne+numTwo;  //displaying all the lists together
 //complexity of O(n)
}

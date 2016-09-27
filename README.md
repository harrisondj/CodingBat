# string 1 

return 'Hello ' + name + '!'

return a + b + b + a

return '<' + tag + '>' + word + '</' + tag + '>'

return out[:2] + word + out[2:]

return str[-2:] * 3

return str[:2]

return str[:len(str) / 2]

return str[1:-1]

if len(a) < len(b):
    return a + b + a
  else:
    return b + a + b

return a[1:] + b[1:]

return str[2:] + str[:2]

# string 2

end = ''
  for x in str:
    end += x * 2
  return end

count = 0
  for i in range(len(str)-1):
    if str[i:i+2] == 'hi':
      count += 1
  return count

count_cat = 0
  count_dog = 0
  for i in range(0, len(str)-2):
    if str[i:i+3] == 'dog':
      count_dog += 1
    if str[i:i+3] == 'cat':
      count_cat += 1
   
  return count_cat == count_dog

count = 0
  for i in range(0, len(str)-3):
    if str[i:i+2] == 'co' and str[i+3] == 'e':
      count += 1
  return count

a = a.lower()
  b = b.lower()
  return (b.endswith(a) or a.endswith(b))

for i in range(len(str)):
    if str[i] != '.' and str[i+1:i+4] == 'xyz':
      return True
  if str[0:3] == 'xyz':
    return True
  return False

# list 1

return nums[0] == 6 or nums[len(nums) - 1] == 6

return len(nums) >= 1 and nums[0] == nums[-1]

return [3,1,4]

return a[0] == b [0] or a[-1] == b[-1]

return sum(nums)

return [nums[1], nums[2], nums[0]]

return nums[::-1]

m = max(nums[0], nums[2])
  return [m,m,m]

return sum(nums[:2])

return [a[1], b[1]]

return [nums[0], nums[-1]]

return 2 in nums or 3 in nums

# list 2

n = 0
  for i in nums:
    if i % 2 == 0:
		  n = n + 1
  return n





max = nums[0]
  
  for x in nums:
	  if x > max:
		  max = x

  min = nums[0]

  for a in nums:
	  if a < min:
		  min = a

  return max - min





sum = 0
  max = nums[0]
  min = nums[0]

  for x in nums:
  	if x > max:
  		max = x

  min = nums[0]

  for a in nums:
  	if a < min:
  		min = a
	
  for b in nums:
  	sum = sum + b

  return (sum - min - max) / (len(nums) - 2)




  if len(nums) == 0:
    return 0
 
  for i in range(0, len(nums)):
    if nums[i] == 13:
      nums[i] = 0
      if i+1 < len(nums): 
        nums[i+1] = 0
  return sum(nums)





 for i in range(0, len(nums)):
    if nums[i] == 6:
      nums[i] = 0
      for x in range(i+1, len(nums)):
        thru = nums[x]
        nums[x] = 0
        if thru == 7:
          break
  return sum(nums)





  for i in range(0, len(nums)-1):
    if nums[i] == 2 and nums[i+1] == 2:
      return True    
  return False
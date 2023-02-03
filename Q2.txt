def solution(numbers):
#     answer = -1
    sum = 0
    
    for i in range(10):
        if numbers.count(i) != 1:
            sum += i
            
    return sum

numbers = [1,2,3,4,6,7,8,0]
answer = solution(numbers)
print(answer)

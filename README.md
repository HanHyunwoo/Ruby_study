# Ruby_study

class Cal
end

c1 = Cal.new(10,10)     # new는 내장되어 있는 메소드,cal클래스를 복제한 인스턴스를 리턴해주는 역할을함, 이것을 c1변수에 담겠다.

# p는 함수인데,실행결과를 출력해주는데 puts보다 더 자세히 출력해줌,  루비는 함수에서 괄호가 생략이 가능하다. 
p c1.add                # 인스턴스를 생성할 때 집어놓은 2개의 결과값을 리턴함
p c1.subtract           # 인스턴스에 저장되어 있는 값을 뺀것을 리턴해줌, 

c2 = Cal.new(30,20)
p c2.add()                # c2인스턴스의 내부적으로 저장될 30과 20을 더한 결과값을 리턴함
p c2.subtract()           # c2인스턴스의 내부적으로 뺄 30과 20을 더한 결과값을 리턴함




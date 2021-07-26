class Stack
  def initialize
    s = @s
  end 
  def make_stack
    @s = []
    @s.push(2) 
    @s.push(3) 
    @s.pop  
  end
end
stack = Stack.new
describe "stack" do
    it "returns the correct result" do
       stack.make_stack 
    end
end

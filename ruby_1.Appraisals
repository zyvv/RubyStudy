# puts "Hello, Ruby!";

# print <<`EOF`	
# 	echo hi there
# 	echo lo there
# EOF

# print <<"foo", <<"bar"
# 	I said foo.
# foo
# 	I said bar.
# bar

# puts "这是主 Ruby 程序"

# END {
# 	puts "停止 Ruby 程序"
# }

# BEGIN {
# 	puts "初始化 Ruby 程序"
# }
# # 注释
# =begin
# 多行
# 注释
# =end

# 123 # Fixnum十进制
# 1_234 # Fixnum带有下划线的十进制
# -500 # 负的Fixnum
# 0377 # 八进制
# 0xff # 十六进制
# 0b1011 # 二进制
# "a".ord # “a”的字符编码
# ?\n # 换行符（0x0a）的编码
# 1234567890 # 大数
# a1 = 0
# a2 = 1_000_000
# a3 = 0xa
# puts a1,a2
# puts a3


# 123.4
# 1.0e6
# 4e20
# f3 = 100000.1
# puts f3

# puts 16**(1/4.0)

# puts 'escape using "\\"';
# puts 'That\'s right';

# puts "相乘 ： #{24*60*60}";
# name = "Ruby"
# puts name
# puts "#{name+", ok"}"

# ary = ["fred", 10, 3.14, "this is a string", "last element", ]
# ary.each do |i|
# 	puts i
# end


# has = colors = {"red" => 0xf00, "green" => 0x0f0, "blue" => 0x00f}
# has.each do |key, value|
# 	print key, " is ", value, "\n"
# end

# (10...15).each do |n| 
# 	print n, " "
# end

# class Vehicle

# 	Number no_of_wheels
# 	Number horsepower
# 	Characters type_of_tank
# 	Number Capacity

# 	Function speeding
# 	{

# 	}

# 	Function driving
# 	{

# 	}

# 	Function halting
# 	{

# 	}
# end

# cust1 = Vehicle.new

class Customer
	@@no_of_customers = 0
	def initialize(id, name, addr)
		@cust_id = id
		@cust_name = name
		@cust_addr = addr
	end
	def display_details()
		puts "Customer id #@cust_id"
		puts "Customer name #@cust_name"
		puts "Customer address #{@cust_addr}"
	end
		
	def total_no_of_customers()
		@@no_of_customers += 1
		puts "Total number of customers: #{@@no_of_customers}"
	end
end

cust1 = Customer.new("1", "John", "wis apr lu")
cust2 = Customer.new("2", "Pour", "New rod lka")

cust1.display_details()
cust1.total_no_of_customers()
cust2.total_no_of_customers()

class Sample
	def hello 
		puts "Hello Ruby!"
	end
end

object = Sample.new
object.hello

print defined? object, "---"



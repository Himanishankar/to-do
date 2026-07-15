# to-do
a command-line-to-do list manager<br>
tasks=[]<br>
while True:
  print("\n1.Add Tasks")
  print("2.View Tasks")
  print("3.Exit")

  choice=input("Choice")<br>

if choice=="1":<br>
  tasks.append(input("Enter tasks:))
elif choice=="2":<br>
  for i,task in enumerate(tasks,1):
    print(f"{i}.{tasks}")
elif choice=="3":<br>
   break

from tkinter import *
from tkinter.ttk import *
a=Tk()
a.title("Calculator")
a.geometry('250x150')
l=Label(a,text='a - ')
l.grid(column=0,row=0)
e1=Entry(a)
e1.grid(column=1,row=0)
l1=Label(a,text='b - ')
l1.grid(column=0,row=1)
e2=Entry(a)
e2.grid(column=1,row=1)
def call():
    s=int(e1.get())+int(e2.get())
    a1.configure(text='Answer: '+str(s))
def sub():  
    s=int(e1.get())-int(e2.get())
    a1.configure(text='Answer: '+str(s))
def mul():  
    s=int(e1.get())*int(e2.get())
    a1.configure(text='Answer: '+str(s))
def div():  
    s=int(e1.get())/int(e2.get())
    a1.configure(text='Answer: '+str(s))
b1=Button(a,text='+',command=call)
b1.grid(column=0,row=2)
b2=Button(a,text='-',command=sub)
b2.grid(column=1,row=2)
b3=Button(a,text='*',command=mul)
b3.grid(column=1,row=3)
b4=Button(a,text='/',command=div)
b4.grid(column=0,row=3)
a1=Label(a,text="")
a1.grid(column=0,row=4)

a.mainloop()

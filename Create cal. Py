from tkinter import *
window=Tk()
window.title("CALCI")
window.geometry("1200x600+100+75")

eq=" "
def show(val):
    global eq
    eq+=val
    disply.config(text=eq)
def clear():
    global eq
    eq=" "
    disply.config(text=eq)
def cal():
    global eq
    res=" "
    if eq != " ":
        try:
            res=eval(eq)
        except:
            res="Invalid equation"
    disply.config(text=res)

b1=Button(window,text="1",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("1"))
b2=Button(window,text="2",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("2"))
b3=Button(window,text="3",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("3"))
b4=Button(window,text="4",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("4"))
b5=Button(window,text="5",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("5"))
b6=Button(window,text="6",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("6"))
b7=Button(window,text="7",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("7"))
b8=Button(window,text="8",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("8"))
b9=Button(window,text="9",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("9"))
b0=Button(window,text="0",padx=72,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("0"))
disply=Label(window,text=" ",width=45,height=2,fg="#FFFFFF",bg="#303F9F")


clearb=Button(window,text="C",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=clear)
plus=Button(window,text="+",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("+"))
minus=Button(window,text="-",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("-"))
div=Button(window,text="÷",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("/"))
modu=Button(window,text="%",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("%"))
multi=Button(window,text="×",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("*"))
dot=Button(window,text=".",width=10,height=3,fg="#FFFFFF",bg="#303F9F",command=lambda:show("."))
equl=Button(window,text="=",padx=72,height=3,fg="#FFFFFF",bg="#303F9F",command=cal)

disply.grid(row=0,column=0,columnspan=7)
plus.grid(row=1,column=0)
minus.grid(row=1,column=1)
multi.grid(row=1,column=2)
clearb.grid(row=1,column=3)
b1.grid(row=2,column=0)
b2.grid(row=2,column=1)
b3.grid(row=2,column=2)
div.grid(row=2,column=3)
b4.grid(row=3,column=0)
b5.grid(row=3,column=1)
b6.grid(row=3,column=2)
modu.grid(row=3,column=3)
b7.grid(row=4,column=0)
b8.grid(row=4,column=1)
b9.grid(row=4,column=2)
equl.grid(row=5,column=2,columnspan=2)
b0.grid(row=5,column=0,columnspan=2)
dot.grid(row=4,column=3)



window.mainloop()

# Alert_Boxes-TKInter-
import tkinter
import tkinter.messagebox

window=tkinter.Tk()
window.title('AlertBox')

tkinter.messagebox.showinfo('Alert Message','This is just an alert message!')

response=tkinter.messagebox.askquestion("Trickey Question",'Do you love Python?')

if response == 1:
    tkinter.Label(window,text='Yes!You love Python!!!').pack()

else:
    tkinter.Label(window,text="NO!You dont love Python!!!").pack()


window.mainloop()

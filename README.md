# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
      

      import matplotlib.pyplot as plt
      x_val = [0,1,2,3,4,5]
      y_val = [0,1,4,9,16,25]
      plt.plot(x_val,y_val)
      plt.show()



![328087468-03db6e2a-beff-45e0-83a2-de2537384c81](https://github.com/user-attachments/assets/741a2fa5-8db4-4d14-90c0-446c54d95da5)



    import matplotlib.pyplot as plt
    x = [1,2,3]
    y = [2,4,1]
    plt.plot(x,y)
    plt.xlabel('x-axis')
    plt.ylabel('y-axis')
    plt.title('My first graph')
    plt.show()





![328087575-7e7559e4-5e09-4bb2-9fb0-8d37d14e6d74](https://github.com/user-attachments/assets/18298543-bf1b-4e1d-b47a-3ad074c8d6e2)


        import matplotlib.pyplot as plt
        x1 = [1,2,3]
        y1 = [2,5,3]
        plt.plot(x1,y1,label = 'line 1')
        x2 = [1,2,3]
        y2 = [3,1,6]
        plt.plot(x2,y2,label = 'line 2')
        plt.xlabel('x-axis')
        plt.ylabel('y-axis')
        plt.title("Two lines on the same graph")
        plt.legend()
        plt.show()
        



![328087646-16e87bfa-27fe-434b-a574-d11ee68cff28](https://github.com/user-attachments/assets/18893a88-567b-417d-8791-c2cc8ddc73a1)



      import matplotlib.pyplot as plt
      import numpy as np
      x = [1,2,3,4,5]
      y1 = [10,12,14,16,18]
      y2 = [5,7,9,11,13]
      y3 = [2,4,6,8,10]
      plt.fill_between(x,y1,color = 'blue')
      plt.fill_between(x,y2,color = 'orange')




![328087730-ab80fa60-f8b0-4aff-8c1d-eafadb00f6f0](https://github.com/user-attachments/assets/89eaa3c0-adc4-4d5b-8856-0a5515a4ebba)


      plt.stackplot(x,y1,y2,y3,labels = ['line1','line2','line3'])
      plt.legend(loc = 'upper left')
      plt.title('Stacked line charts')
      plt.xlabel('x-axis')
      plt.ylabel('y-axis')
      plt.show()

![328087826-848cf02d-6463-4b98-aae1-d22ccc233810](https://github.com/user-attachments/assets/883f2f73-76b7-4823-ac5f-b43e6b9991bb)


      import numpy as np
      import matplotlib.pyplot as plt
      val = [2,4,7,3]
      names = ['A','B','C','D']
      plt.bar(names, val,color = 'purple')
      plt.show()



![328089091-1b38caaf-f80c-4524-8233-7d8da40120e5](https://github.com/user-attachments/assets/9e235ee2-41a5-427c-a94f-20eb17186c50)



      import matplotlib.pyplot as plt
      import numpy as np
      ages = [2,6,4,12,13,12,16,18,18,19,26,24,39,34,45,42,54,56,90,56,86,79]
      range = (0,100)
      bins = 10
      plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
      plt.xlabel('age')
      plt.ylabel('no of people')
      plt.title('histogram')
      plt.show()


![328089047-16d3a251-b5bf-4451-9dbf-b43d11d7d5ba](https://github.com/user-attachments/assets/53fe3988-5dc5-456b-99cb-801148d5d4e1)



      import matplotlib.pyplot as plt
      import numpy as np
      np.random.seed(0)
      data=np.random.normal(loc=0,scale=1,size=100)
      data




![328088984-4d86e55a-fcd9-4f44-9bd2-599e3f8723d0](https://github.com/user-attachments/assets/cfbe99ff-d4f5-444b-a596-8694085306f5)

    fig,ax=plt.subplots()
    ax.boxplot(data)
    ax.set_xlabel("data")
    ax.set_ylabel("values")
    ax.set_title("box plot")
          



![328088940-d6e1b3e1-0d91-497f-a303-feb9561dbb29](https://github.com/user-attachments/assets/fd9b0242-bcc6-49d5-a684-a5351e8a36ae)


      import matplotlib.pyplot as plt
      activities=['eat','sleep','work','play']
      slices=[3,7,8,6]
      colors=['r','y','g','b']
      plt.pie(slices,labels = slices,colors=colors,startangle=90,shadow = True,explode = (0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
      plt.legend()
      plt.show()


![328088117-de3fe53c-40f8-4ba2-9fac-8b4dc36e5010](https://github.com/user-attachments/assets/9a772a1d-b4e9-4988-90b0-1bb9de293d35)



# Result:
 Thus the program is executed successfully.

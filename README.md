import urllib.request

inputvar=input("Enter package name: ")
urlip = "https://captmadkatz.github.io/" +str(inputvar)
filename = inputvar +str(".py")
#print(inputvar)
#print(urlip)
#print(filename)
urllib.request.urlretrieve(urlip, filename)

    

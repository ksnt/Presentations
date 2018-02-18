# Presentation Sample Created using GitPitch 

This is a sample presentation!

author:ksnt

---

### How to access the presentation file

- Step 1. Create PITCHME.md
- Step 2. Commit PITCHME.md
- Step 3. Access https://gitpitch.com/$user/$repo/$branch

---
### Mathematical Expression

$$\frac{\partial^2 p}{\partial t^2} = c^2 \nabla^2 p$$

You can easily embed mathematical formula using LaTex expression in markdown file!  

---

### Source Code

```python

# bubble sort  

def bubble_sort(a_list):
	for pass_num in range(len(a_list)-1,0,-1):
		for i in range(pass_num):
			if a_list[i] > a_list[i+1]:
				temp = a_list[i]
				a_list[i] = a_list[i+1]
				a_list[i+1] = temp

a_list = [54,26,93,17,77,31,44,55,20]
bubble_sort(a_list)
print(a_list)

```

---

![Gitpitch Picture](https://github.com/ksnt/Presentations/blob/master/gitpitch.png)

Now image file is not shown...

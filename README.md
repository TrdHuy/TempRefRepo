Cách set up để về trạng thái HEAD detach from commit
1, Mở cmd tại đây
2, check out sang nhánh orgin master: git checkout origin/master
3, Tạo 1 CL và commit: git add . -> git commit -m 'test'
4, push lên master: git push origin HEAD:master
5, kiểm tra lại với trạng thái detach commit: git status

### atrox
![image](https://github.com/TrdHuy/TempRefRepo/assets/32306489/5f6eec69-a54c-4213-8e8d-b63fef55cdfc)

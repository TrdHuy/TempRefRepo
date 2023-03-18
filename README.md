Cách set up để về trạng thái HEAD detach from commit
1, Mở cmd tại đây
2, check out sang nhánh orgin master: git checkout origin/master
3, Tạo 1 CL và commit: git add . -> git commit -m 'test'
4, push lên master: git push origin HEAD:master
5, kiểm tra lại với trạng thái detach commit: git status
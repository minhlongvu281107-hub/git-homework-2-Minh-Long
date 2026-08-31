hello
gudbai
part 3
giai thich A3:
khi chuyển từ nhánh week2 về master dòng chữ vừa thêm bị biến mất vì những thay đổi đó chỉ được lưu trên nhánh week2,ta chưa merge vào nhánh master nen nhánh master vẫn giữ nguyên trạng thái cũ

 git branch --merged
* master
  week2.md
  week2b

 git branch --no-merged
  wip

c2 : $ git branch -vv
  master           6956d4e Merge branch 'week2' into week2b
  week2.md         8f1635d tao week2.md
* work-in-progress 62c7b97 [origin/work-in-progress: ahead 1] them text lam partc

giải thihcs D4
Lệnh rebase đã cấu trúc lại lịch sử commit gọn gàng hơn .Git đã gộp commit của nhánh experiment nối tiếp vào sau commit mới nhất của master .
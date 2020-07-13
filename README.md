# Dotfiles
My configuration files that start with a dot

## vimrc

* CentOS7

```sh
git clone https://github.com/trangnth/Dotfiles
cd Dotfiles/vim
echo y | cp vimrc /root/.vimrc
chmod +x vimsetup.sh
./vimsetup.sh
```

* `Ctrl + n` : Mở cây thư mục

	* `i`: mở một file được chọn (split theo chiều ngang)
	* `s`: mở một file được chọn (split theo chiều dọc)
	* `Shift + i`: hiển thị các file ẩn
	* `Ctrl + w + ->`: di chuyển giữa các windows 
	* `t`: mở file trong một tab mới 
	* `tab_number + gt`: di chuyển giữa các tab
	* `p`: tới thư mục cha
	* `r`: refresh thư mục hiện tại 

* Giao diện tương tự

<img src="img/1.png" alt="">
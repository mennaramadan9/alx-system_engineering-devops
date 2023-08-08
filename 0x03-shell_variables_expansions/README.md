alias ls="rm"
echo "hello $()"
export PATH="$PATH:/action"
echo $PATH | tr ':' '\n' | wc -l

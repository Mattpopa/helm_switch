For fast switching between helm2 and helm3 add `helm_switch` at ` ~/.local/sources/helm_switch` and then include `helm_switch` to your bash profile:

    echo 'source ~/.local/sources/helm_switch >> ~/.bash_profile'
    echo 'export PATH="~/.local/bin:$PATH" >> ~/.bash_profile'

then use `helm3_switch` when you want helm3, and `helm2_switch` back to helm2

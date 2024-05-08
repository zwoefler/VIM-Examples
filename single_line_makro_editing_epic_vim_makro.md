# What we have
type Color struct {
    Red         byte
    Blue        byte
    Green       byte
    Foreground  bool
}

# What we want!
type Color struct {
    Red         byte `json:"red"`
    Blue        byte `json:"blue"`
    Green       byte `json:"green"`
    Foreground  bool `json:"foreground"`
}



# How to do it:
Go to line 3 and press the following:
qa (Starting a makro)
^ yiw A `json:" <ESC> p b ~ A "` 
q (Stopping the Makro)

@a (Execute the makro)


# Visuals
# Using visuals to explain difference:
# viw vs vaw vs.
    Red         byte `json:"red"`


## 📚 Sources
🔗 URL: https://www.youtube.com/shorts/W2dmrZbj-jI

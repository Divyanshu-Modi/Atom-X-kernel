dtb-$(CONFIG_DTB_RT2880_EVAL)	+= rt2880_eval.dtb
dtb-$(CONFIG_DTB_RT305X_EVAL)	+= rt3052_eval.dtb
dtb-$(CONFIG_DTB_RT3883_EVAL)	+= rt3883_eval.dtb
dtb-$(CONFIG_DTB_MT7620A_EVAL)	+= mt7620a_eval.dtb

obj-y				+= $(patsubst %.dtb, %.dtb.o, $(dtb-y))

# Force kbuild to make empty built-in.a if necessary
obj-				+= dummy.o

always				:= $(dtb-y)
clean-files			:= *.dtb *.dtb.S

ifeq ($(KP_MODULE_ROOT),)
KP_MODULE_ROOT := $(KERNEL_SRC)/$(M)
endif

all: modules

clean:
	$(MAKE) -C $(KERNEL_SRC) M=$(M) clean

%:
	$(MAKE) -C $(KERNEL_SRC) M=$(M) $@ $(KBUILD_OPTIONS)

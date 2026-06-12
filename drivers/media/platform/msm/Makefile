#
# Makefile for the QCOM spcific video device drivers
# based on V4L2.
#

obj-$(CONFIG_MSM_VIDC_V4L2)     += vidc/
obj-$(CONFIG_MSM_WFD) += wfd/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
ifneq ($(filter y,$(CONFIG_WT88047_CAMERA) $(CONFIG_WT86621_CAMERA)),)
obj-$(CONFIG_MSMB_CAMERA) += camera_wt88047_v2/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif
obj-$(CONFIG_MSM_VPU) += vpu/

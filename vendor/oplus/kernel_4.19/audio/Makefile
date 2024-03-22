#
# Copyright (C) 2015 MediaTek Inc.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.
#

# Jun.Liang@MULTIMEDIA.AUDIODRIVER.MACHINE, 2020/08/26, Add for oplus extend audio
obj-y += driver/
# Zhao.Pan@MULTIMEDIA.AUDIODRIVER.SMARTPA, 2020/04/28, add for aw87339 PA
obj-y += aw87339/
# Jingjing.Jiang@MULTIMEDIA.AUDIODRIVER.SMARTPA, 2020/05/19, add for tfa98xx smartPA
obj-y += tfa98xx/
# Jun.Liang@MULTIMEDIA.AUDIODRIVER.SMARTPA, 2020/09/08, add for SIA PA ALGO
ifeq ($(CONFIG_SND_SOC_SIA81XX_V1_2_0),y)
obj-$(CONFIG_SIA_PA_ALGO) += sia81xx_1.2.0/
else
# Yujie.Xiang@MULTIMEDIA.AUDIODRIVER.SMARTPA, 2022/06/21, add for SIA PA
obj-$(CONFIG_SIA_PA_ALGO) += sia81xx/
obj-$(CONFIG_SIA_PA_ALGO_MT6833) += sia81xx/
endif
# add for SIA91XX PA
obj-$(CONFIG_SND_SOC_SIA91XX_V3_1_0) += sia91xx_v3.1.0/
# Tao.Ban@MULTIMEDIA.AUDIODRIVER.SMARTPA, 2022/01/11, add for aw882xx_v1.10.0 driver
obj-$(CONFIG_SND_SOC_CODEC_AW882XX) += aw882xx_v1.10.0/
# Wang.kun@MULTIMEDIA.AUDIODRIVER.SMARTPA, 2020/12/16, add for aw882xx smartPA
obj-$(CONFIG_SND_SOC_CODEC_AW88264) += aw882xx/
# Haiping.Bai@PSW.MM.AudioDriver.CODEC, 2021/11/25, add PA Driver
obj-$(CONFIG_SND_SOC_AW87XXX) += awinic/
obj-$(CONFIG_SND_SOC_OPLUS_PA_MANAGER) += oplus_speaker_manager/oplus_speaker_manager.o

# Yunfan.Li@PSW.MM.AudioDriver.PA, 2022/05/27, add PA Driver2.6
obj-$(CONFIG_SND_SOC_AW87XXX_2_X_0) += awinic_2.x.0/

# Yongpei.Yao@MULTIMEDIA.AUDIODRIVER.HEADSET, 2021/02/23, add for fsa switch
obj-$(CONFIG_SND_SOC_FSA) += fsa44xx/
# add for Audio Type-C switch
obj-$(CONFIG_SND_SOC_OPLUS_TYPEC_SWITCH) += oplus_typec_switch/
# Jianqing.Liao@MULTIMEDIA.AUDIODRIVER.TFA_HAPTIC, 2021/04/15, add for tfa haptic
obj-$(CONFIG_SND_SOC_TFA_HAPTIC) += tfa_haptic/

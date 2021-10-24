# Automatically generated makefile, created by the Projucer
# Don't edit this file! Your changes will be overwritten when you re-save the Projucer project!

# build with "V=1" for verbose builds
ifeq ($(V), 1)
V_AT =
else
V_AT = @
endif

# (this disables dependency generation if multiple architectures are set)
DEPFLAGS := $(if $(word 2, $(TARGET_ARCH)), , -MMD)

ifndef STRIP
  STRIP=strip
endif

ifndef AR
  AR=ar
endif

ifndef CONFIG
  CONFIG=Debug
endif

JUCE_ARCH_LABEL := $(shell uname -m)

ifeq ($(CONFIG),Debug)
  JUCE_BINDIR := build
  JUCE_LIBDIR := build
  JUCE_OBJDIR := build/intermediate/Debug
  JUCE_OUTDIR := ../../../Plugins

  ifeq ($(TARGET_ARCH),)
    TARGET_ARCH := 
  endif

  JUCE_CPPFLAGS := $(DEPFLAGS) "-DLINUX=1" "-DDEBUG=1" "-D_DEBUG=1" "-DPD_INTERNAL=1" "-DJUCE_VST3_CAN_REPLACE_VST2=0" "-DPD=1" "-DPDINSTANCE=1" "-DCAMOMILE=1" "-DJUCER_LINUX_MAKE_6D53C8B4=1" "-DJUCE_APP_VERSION=1.0.7" "-DJUCE_APP_VERSION_HEX=0x10007" $(shell pkg-config --cflags freetype2) -pthread -I../../../Juce/modules/juce_audio_processors/format_types/VST3_SDK -I../../../Dependencies/Vst2 -I../../JuceLibraryCode -I../../../Juce/modules -I../../../Dependencies/LibPd/pure-data/src -I../../../Dependencies/LibPd/libpd_wrapper -I../../../Dependencies/LibPd/libpd_wrapper/util -I../../../Dependencies/LibPd/cpp -I../../../Source/Pd/ELSE -I../../../Source/Pd/ELSE/shared $(CPPFLAGS)

  JUCE_CPPFLAGS_VST3 :=  "-DJucePlugin_Build_VST=0" "-DJucePlugin_Build_VST3=1" "-DJucePlugin_Build_AU=0" "-DJucePlugin_Build_AUv3=0" "-DJucePlugin_Build_RTAS=0" "-DJucePlugin_Build_AAX=0" "-DJucePlugin_Build_Standalone=0" "-DJucePlugin_Build_Unity=0"
  JUCE_CFLAGS_VST3 := -fPIC -fvisibility=hidden
  JUCE_LDFLAGS_VST3 := -shared -Wl,--no-undefined
  JUCE_VST3DIR := Camomile.vst3
  VST3_PLATFORM_ARCH := $(shell $(CXX) make_helpers/arch_detection.cpp 2>&1 | tr '\n' ' ' | sed "s/.*JUCE_ARCH \([a-zA-Z0-9_-]*\).*/\1/")
  JUCE_VST3SUBDIR := Contents/$(VST3_PLATFORM_ARCH)-linux
  JUCE_TARGET_VST3 := $(JUCE_VST3DIR)/$(JUCE_VST3SUBDIR)/Camomile.so
  JUCE_VST3DESTDIR := $(HOME)/.vst3
  JUCE_COPYCMD_VST3 := $(JUCE_OUTDIR)/$(JUCE_VST3DIR) $(JUCE_VST3DESTDIR)

  JUCE_CPPFLAGS_SHARED_CODE :=  "-DJucePlugin_Build_VST=0" "-DJucePlugin_Build_VST3=1" "-DJucePlugin_Build_AU=0" "-DJucePlugin_Build_AUv3=0" "-DJucePlugin_Build_RTAS=0" "-DJucePlugin_Build_AAX=0" "-DJucePlugin_Build_Standalone=0" "-DJucePlugin_Build_Unity=0" "-DJUCE_SHARED_CODE=1"
  JUCE_TARGET_SHARED_CODE := Camomile.a

  JUCE_CFLAGS += $(JUCE_CPPFLAGS) $(TARGET_ARCH) -fPIC -g -ggdb -O0 -fPIC $(CFLAGS)
  JUCE_CXXFLAGS += $(JUCE_CFLAGS) -std=c++14 $(CXXFLAGS)
  JUCE_LDFLAGS += $(TARGET_ARCH) -L$(JUCE_BINDIR) -L$(JUCE_LIBDIR) -L../../../Dependencies/LibPdBuild $(shell pkg-config --libs freetype2) -fvisibility=hidden -lrt -ldl -lpthread -lpd-multi $(LDFLAGS)

  CLEANCMD = rm -rf $(JUCE_OUTDIR)/$(TARGET) $(JUCE_OBJDIR)
endif

ifeq ($(CONFIG),Release)
  JUCE_BINDIR := build
  JUCE_LIBDIR := build
  JUCE_OBJDIR := build/intermediate/Release
  JUCE_OUTDIR := ../../../Plugins

  ifeq ($(TARGET_ARCH),)
    TARGET_ARCH := 
  endif

  JUCE_CPPFLAGS := $(DEPFLAGS) "-DLINUX=1" "-DNDEBUG=1" "-DPD_INTERNAL=1" "-DJUCE_VST3_CAN_REPLACE_VST2=0" "-DPD=1" "-DPDINSTANCE=1" "-DCAMOMILE=1" "-DJUCER_LINUX_MAKE_6D53C8B4=1" "-DJUCE_APP_VERSION=1.0.7" "-DJUCE_APP_VERSION_HEX=0x10007" $(shell pkg-config --cflags freetype2) -pthread -I../../../Juce/modules/juce_audio_processors/format_types/VST3_SDK -I../../../Dependencies/Vst2 -I../../JuceLibraryCode -I../../../Juce/modules -I../../../Dependencies/LibPd/pure-data/src -I../../../Dependencies/LibPd/libpd_wrapper -I../../../Dependencies/LibPd/libpd_wrapper/util -I../../../Dependencies/LibPd/cpp -I../../../Source/Pd/ELSE -I../../../Source/Pd/ELSE/shared $(CPPFLAGS)

  JUCE_CPPFLAGS_VST3 :=  "-DJucePlugin_Build_VST=0" "-DJucePlugin_Build_VST3=1" "-DJucePlugin_Build_AU=0" "-DJucePlugin_Build_AUv3=0" "-DJucePlugin_Build_RTAS=0" "-DJucePlugin_Build_AAX=0" "-DJucePlugin_Build_Standalone=0" "-DJucePlugin_Build_Unity=0"
  JUCE_CFLAGS_VST3 := -fPIC -fvisibility=hidden
  JUCE_LDFLAGS_VST3 := -shared -Wl,--no-undefined
  JUCE_VST3DIR := Camomile.vst3
  VST3_PLATFORM_ARCH := $(shell $(CXX) make_helpers/arch_detection.cpp 2>&1 | tr '\n' ' ' | sed "s/.*JUCE_ARCH \([a-zA-Z0-9_-]*\).*/\1/")
  JUCE_VST3SUBDIR := Contents/$(VST3_PLATFORM_ARCH)-linux
  JUCE_TARGET_VST3 := $(JUCE_VST3DIR)/$(JUCE_VST3SUBDIR)/Camomile.so
  JUCE_VST3DESTDIR := $(HOME)/.vst3
  JUCE_COPYCMD_VST3 := $(JUCE_OUTDIR)/$(JUCE_VST3DIR) $(JUCE_VST3DESTDIR)

  JUCE_CPPFLAGS_SHARED_CODE :=  "-DJucePlugin_Build_VST=0" "-DJucePlugin_Build_VST3=1" "-DJucePlugin_Build_AU=0" "-DJucePlugin_Build_AUv3=0" "-DJucePlugin_Build_RTAS=0" "-DJucePlugin_Build_AAX=0" "-DJucePlugin_Build_Standalone=0" "-DJucePlugin_Build_Unity=0" "-DJUCE_SHARED_CODE=1"
  JUCE_TARGET_SHARED_CODE := Camomile.a

  JUCE_CFLAGS += $(JUCE_CPPFLAGS) $(TARGET_ARCH) -fPIC -O3 -fPIC $(CFLAGS)
  JUCE_CXXFLAGS += $(JUCE_CFLAGS) -std=c++14 $(CXXFLAGS)
  JUCE_LDFLAGS += $(TARGET_ARCH) -L$(JUCE_BINDIR) -L$(JUCE_LIBDIR) -L../../../Dependencies/LibPdBuild $(shell pkg-config --libs freetype2) -fvisibility=hidden -lrt -ldl -lpthread -lpd-multi $(LDFLAGS)

  CLEANCMD = rm -rf $(JUCE_OUTDIR)/$(TARGET) $(JUCE_OBJDIR)
endif

OBJECTS_ALL := \

OBJECTS_VST3 := \
  $(JUCE_OBJDIR)/include_juce_audio_plugin_client_VST3_dd633589.o \

OBJECTS_SHARED_CODE := \
  $(JUCE_OBJDIR)/PluginProcessor_319d19ef.o \
  $(JUCE_OBJDIR)/PluginProcessorBuses_ff06f3c9.o \
  $(JUCE_OBJDIR)/PluginProcessorReceive_8862f77e.o \
  $(JUCE_OBJDIR)/PluginEditor_ef07f2fa.o \
  $(JUCE_OBJDIR)/PluginEditorComponents_6d39f4f0.o \
  $(JUCE_OBJDIR)/PluginEditorConsole_207d0487.o \
  $(JUCE_OBJDIR)/PluginEditorInteraction_f8a5a242.o \
  $(JUCE_OBJDIR)/PluginEditorObject_7e10b319.o \
  $(JUCE_OBJDIR)/PluginEnvironment_564e0cf0.o \
  $(JUCE_OBJDIR)/PluginParameter_9c951d86.o \
  $(JUCE_OBJDIR)/PluginParser_125664ac.o \
  $(JUCE_OBJDIR)/PluginLookAndFeel_1523addb.o \
  $(JUCE_OBJDIR)/buffer_e0c59c87.o \
  $(JUCE_OBJDIR)/file_ee2b0b43.o \
  $(JUCE_OBJDIR)/grow_f060581a.o \
  $(JUCE_OBJDIR)/magic_3b9753d0.o \
  $(JUCE_OBJDIR)/mifi_fa1a4c66.o \
  $(JUCE_OBJDIR)/random_4a6ad84a.o \
  $(JUCE_OBJDIR)/s_utf8_554e14c4.o \
  $(JUCE_OBJDIR)/above~_ad5c134e.o \
  $(JUCE_OBJDIR)/add~_8798d5ca.o \
  $(JUCE_OBJDIR)/adsr~_6c50f5d9.o \
  $(JUCE_OBJDIR)/allpass.2nd~_611507df.o \
  $(JUCE_OBJDIR)/allpass.rev~_cdd48ac4.o \
  $(JUCE_OBJDIR)/args_885f52aa.o \
  $(JUCE_OBJDIR)/asr~_8872938b.o \
  $(JUCE_OBJDIR)/autofade~_43f14650.o \
  $(JUCE_OBJDIR)/autofade2~_3a161dc4.o \
  $(JUCE_OBJDIR)/balance~_a61ba5af.o \
  $(JUCE_OBJDIR)/bandpass~_e4a9a955.o \
  $(JUCE_OBJDIR)/bandstop~_a38eb3c4.o \
  $(JUCE_OBJDIR)/bend.in_73612757.o \
  $(JUCE_OBJDIR)/bend.out_f91c7fe6.o \
  $(JUCE_OBJDIR)/bicoeff_e2cc2f6f.o \
  $(JUCE_OBJDIR)/biquads~_5b8713c6.o \
  $(JUCE_OBJDIR)/blocksize~_1676733d.o \
  $(JUCE_OBJDIR)/break_b84dbf1c.o \
  $(JUCE_OBJDIR)/brown~_63b32315.o \
  $(JUCE_OBJDIR)/buffer_obj_c2dea585.o \
  $(JUCE_OBJDIR)/button_ac401bf.o \
  $(JUCE_OBJDIR)/canvas.active_b1e71739.o \
  $(JUCE_OBJDIR)/canvas.bounds_96865f28.o \
  $(JUCE_OBJDIR)/canvas.edit_bf1f2cbd.o \
  $(JUCE_OBJDIR)/canvas.gop_509e217f.o \
  $(JUCE_OBJDIR)/canvas.mouse_df6701dc.o \
  $(JUCE_OBJDIR)/canvas.name_ce521cfe.o \
  $(JUCE_OBJDIR)/canvas.pos_511d004b.o \
  $(JUCE_OBJDIR)/canvas.setname_cef2b0a4.o \
  $(JUCE_OBJDIR)/canvas.vis_516ed317.o \
  $(JUCE_OBJDIR)/canvas.wname_ed93e979.o \
  $(JUCE_OBJDIR)/canvas.zoom_e3929446.o \
  $(JUCE_OBJDIR)/ceil_8b12a0d2.o \
  $(JUCE_OBJDIR)/ceil~_d7429fb6.o \
  $(JUCE_OBJDIR)/cents2ratio_92c0981.o \
  $(JUCE_OBJDIR)/cents2ratio~_1c564ce7.o \
  $(JUCE_OBJDIR)/chance_a22df541.o \
  $(JUCE_OBJDIR)/chance~_a391d927.o \
  $(JUCE_OBJDIR)/changed_a3c9d591.o \
  $(JUCE_OBJDIR)/changed~_d57202d7.o \
  $(JUCE_OBJDIR)/changed2~_d8acf21d.o \
  $(JUCE_OBJDIR)/click_e3302d65.o \
  $(JUCE_OBJDIR)/clipnoise~_4f910a01.o \
  $(JUCE_OBJDIR)/cmul~_e5927eba.o \
  $(JUCE_OBJDIR)/coin_8b9f935e.o \
  $(JUCE_OBJDIR)/coin~_e853feaa.o \
  $(JUCE_OBJDIR)/colors_2754007d.o \
  $(JUCE_OBJDIR)/comb.filt~_eee7b4b3.o \
  $(JUCE_OBJDIR)/comb.rev~_ea6ef2e5.o \
  $(JUCE_OBJDIR)/common.div_f012f19b.o \
  $(JUCE_OBJDIR)/cosine~_2afd0542.o \
  $(JUCE_OBJDIR)/crackle~_61704878.o \
  $(JUCE_OBJDIR)/crossover~_6048ae77.o \
  $(JUCE_OBJDIR)/ctl.in_2c3b06e5.o \
  $(JUCE_OBJDIR)/ctl.out_5b7e9218.o \
  $(JUCE_OBJDIR)/cusp~_f31ee62c.o \
  $(JUCE_OBJDIR)/decay~_6e194e11.o \
  $(JUCE_OBJDIR)/decay2~_54ef0e23.o \
  $(JUCE_OBJDIR)/default_f38399de.o \
  $(JUCE_OBJDIR)/del~_8cc91a20.o \
  $(JUCE_OBJDIR)/detect~_ddf45b58.o \
  $(JUCE_OBJDIR)/dir_d300192a.o \
  $(JUCE_OBJDIR)/dollsym_5263ac79.o \
  $(JUCE_OBJDIR)/downsample~_e9ef988f.o \
  $(JUCE_OBJDIR)/drive~_29263a41.o \
  $(JUCE_OBJDIR)/dust~_2806f2e9.o \
  $(JUCE_OBJDIR)/dust2~_d8b6044b.o \
  $(JUCE_OBJDIR)/else_8ee36806.o \
  $(JUCE_OBJDIR)/envgen~_8672fab8.o \
  $(JUCE_OBJDIR)/eq~_d31200af.o \
  $(JUCE_OBJDIR)/f2s~_8d674b44.o \
  $(JUCE_OBJDIR)/factor_6b49c09c.o \
  $(JUCE_OBJDIR)/fader~_6c2cc2d5.o \
  $(JUCE_OBJDIR)/fbdelay~_9c989664.o \
  $(JUCE_OBJDIR)/fbsine~_a15b0af2.o \
  $(JUCE_OBJDIR)/fbsine2~_89e4ed62.o \
  $(JUCE_OBJDIR)/fdn.rev~_80ea8ec6.o \
  $(JUCE_OBJDIR)/ffdelay~_edaa5268.o \
  $(JUCE_OBJDIR)/float2bits_384edf69.o \
  $(JUCE_OBJDIR)/float2sig~_554b8270.o \
  $(JUCE_OBJDIR)/floor_823cfae9.o \
  $(JUCE_OBJDIR)/floor~_c563887f.o \
  $(JUCE_OBJDIR)/fold_90bf54ce.o \
  $(JUCE_OBJDIR)/fold~_872c6b3a.o \
  $(JUCE_OBJDIR)/fontsize_58be31dd.o \
  $(JUCE_OBJDIR)/format_6910b544.o \
  $(JUCE_OBJDIR)/freq.shift~_8576c3cf.o \
  $(JUCE_OBJDIR)/function_50bed6e5.o \
  $(JUCE_OBJDIR)/function~_c71d2c03.o \
  $(JUCE_OBJDIR)/gate2imp~_ec2b6f16.o \
  $(JUCE_OBJDIR)/gaussian~_9c8b5b00.o \
  $(JUCE_OBJDIR)/gbman~_1815990c.o \
  $(JUCE_OBJDIR)/gcd_d32770e5.o \
  $(JUCE_OBJDIR)/giga.rev~_a2cd504a.o \
  $(JUCE_OBJDIR)/glide~_2266b646.o \
  $(JUCE_OBJDIR)/glide2~_2a4eac8e.o \
  $(JUCE_OBJDIR)/gray~_c09fb998.o \
  $(JUCE_OBJDIR)/gui_d32fb258.o \
  $(JUCE_OBJDIR)/henon~_2123995b.o \
  $(JUCE_OBJDIR)/highpass~_95f70d48.o \
  $(JUCE_OBJDIR)/highshelf~_ba898143.o \
  $(JUCE_OBJDIR)/hot_d33b38ea.o \
  $(JUCE_OBJDIR)/hz2rad_11c7ac82.o \
  $(JUCE_OBJDIR)/hz2rad~_272f0a06.o \
  $(JUCE_OBJDIR)/ikeda~_b66da0cb.o \
  $(JUCE_OBJDIR)/imp~_95c3e2bf.o \
  $(JUCE_OBJDIR)/imp2~_22970f35.o \
  $(JUCE_OBJDIR)/impseq~_46b9aae8.o \
  $(JUCE_OBJDIR)/impulse~_64c0cf6.o \
  $(JUCE_OBJDIR)/impulse2~_c3142bde.o \
  $(JUCE_OBJDIR)/initmess_8f77ca15.o \
  $(JUCE_OBJDIR)/int~_95d3cbbc.o \
  $(JUCE_OBJDIR)/keyboard_ab60f34.o \
  $(JUCE_OBJDIR)/lag~_9a353b39.o \
  $(JUCE_OBJDIR)/lag2~_ac50c5fb.o \
  $(JUCE_OBJDIR)/lastvalue~_6a993590.o \
  $(JUCE_OBJDIR)/latoocarfian~_16cea356.o \
  $(JUCE_OBJDIR)/lb_e5c9b303.o \
  $(JUCE_OBJDIR)/lfnoise~_c303102b.o \
  $(JUCE_OBJDIR)/limit_ba64f2d8.o \
  $(JUCE_OBJDIR)/lincong~_efd1d15.o \
  $(JUCE_OBJDIR)/loadbanger_2b6d198.o \
  $(JUCE_OBJDIR)/logistic~_c9ae407b.o \
  $(JUCE_OBJDIR)/loop_9afdf2b1.o \
  $(JUCE_OBJDIR)/lorenz~_25b4da59.o \
  $(JUCE_OBJDIR)/lowpass~_c79b5e86.o \
  $(JUCE_OBJDIR)/lowshelf~_bd6f57c5.o \
  $(JUCE_OBJDIR)/match~_5e81cc26.o \
  $(JUCE_OBJDIR)/median~_ccad0791.o \
  $(JUCE_OBJDIR)/merge_e8bd2015.o \
  $(JUCE_OBJDIR)/message_f7376a24.o \
  $(JUCE_OBJDIR)/messbox_f7496bf0.o \
  $(JUCE_OBJDIR)/midi_9c5923ee.o \
  $(JUCE_OBJDIR)/mouse_f9fd5142.o \
  $(JUCE_OBJDIR)/mov.avg~_b0cd2e13.o \
  $(JUCE_OBJDIR)/mov.rms~_cd56318d.o \
  $(JUCE_OBJDIR)/mtx~_9cfd8cba.o \
  $(JUCE_OBJDIR)/nbang_17987803.o \
  $(JUCE_OBJDIR)/note_9e69c07f.o \
  $(JUCE_OBJDIR)/note.in_b47c583e.o \
  $(JUCE_OBJDIR)/note.out_db676bdf.o \
  $(JUCE_OBJDIR)/nyquist~_21b9eb30.o \
  $(JUCE_OBJDIR)/op~_d39e775a.o \
  $(JUCE_OBJDIR)/openfile_89124653.o \
  $(JUCE_OBJDIR)/oscilloscope_50ce455c.o \
  $(JUCE_OBJDIR)/oscilloscope_dialog_f88af155.o \
  $(JUCE_OBJDIR)/pack2_7fca20d6.o \
  $(JUCE_OBJDIR)/pad_d3a55bb0.o \
  $(JUCE_OBJDIR)/pan2~_804c5786.o \
  $(JUCE_OBJDIR)/pan4~_804d4044.o \
  $(JUCE_OBJDIR)/panic_8064f294.o \
  $(JUCE_OBJDIR)/parabolic~_5a57d632.o \
  $(JUCE_OBJDIR)/peak~_8682719c.o \
  $(JUCE_OBJDIR)/pgm.in_c4ae248a.o \
  $(JUCE_OBJDIR)/pgm.out_d16f2913.o \
  $(JUCE_OBJDIR)/pic_d3a8fae7.o \
  $(JUCE_OBJDIR)/pimp~_8e0133ff.o \
  $(JUCE_OBJDIR)/pimpmul~_24edf023.o \
  $(JUCE_OBJDIR)/pinknoise~_d5016227.o \
  $(JUCE_OBJDIR)/pluck~_ddc0144a.o \
  $(JUCE_OBJDIR)/pmosc~_94710e9.o \
  $(JUCE_OBJDIR)/power~_7ffbd4e6.o \
  $(JUCE_OBJDIR)/properties_f4ab9f80.o \
  $(JUCE_OBJDIR)/pulse~_ab5b49d2.o \
  $(JUCE_OBJDIR)/pulsecount~_cc554805.o \
  $(JUCE_OBJDIR)/pulsediv~_cb3f7983.o \
  $(JUCE_OBJDIR)/quad~_d6b30834.o \
  $(JUCE_OBJDIR)/quantizer_1cbae2fe.o \
  $(JUCE_OBJDIR)/quantizer~_7aa2a30a.o \
  $(JUCE_OBJDIR)/rad2hz_47e793dc.o \
  $(JUCE_OBJDIR)/rad2hz~_b50c0dec.o \
  $(JUCE_OBJDIR)/ramp~_ea26e589.o \
  $(JUCE_OBJDIR)/rampnoise~_2e4bd0c3.o \
  $(JUCE_OBJDIR)/rand.f_5b9df8aa.o \
  $(JUCE_OBJDIR)/rand.f~_182242de.o \
  $(JUCE_OBJDIR)/rand.i_5b9e03ed.o \
  $(JUCE_OBJDIR)/rand.i~_18239ffb.o \
  $(JUCE_OBJDIR)/rand.seq_ecd2e2a3.o \
  $(JUCE_OBJDIR)/randpulse~_41a654f7.o \
  $(JUCE_OBJDIR)/randpulse2~_f302e3fd.o \
  $(JUCE_OBJDIR)/range~_5be199ae.o \
  $(JUCE_OBJDIR)/ratio2cents_7e3bd981.o \
  $(JUCE_OBJDIR)/ratio2cents~_49407ce7.o \
  $(JUCE_OBJDIR)/rec_d3c3586d.o \
  $(JUCE_OBJDIR)/receiver_60f6233c.o \
  $(JUCE_OBJDIR)/rescale_c1425114.o \
  $(JUCE_OBJDIR)/rescale~_6708f7b4.o \
  $(JUCE_OBJDIR)/resonant~_f60b3ad3.o \
  $(JUCE_OBJDIR)/resonant2~_cb3ab9a1.o \
  $(JUCE_OBJDIR)/retrieve_f5b31a49.o \
  $(JUCE_OBJDIR)/rint_a4e6140a.o \
  $(JUCE_OBJDIR)/rint~_f7dd937e.o \
  $(JUCE_OBJDIR)/rms~_a520dd73.o \
  $(JUCE_OBJDIR)/rotate~_29389a0.o \
  $(JUCE_OBJDIR)/routeall_8afce1c5.o \
  $(JUCE_OBJDIR)/router_4d21c816.o \
  $(JUCE_OBJDIR)/routetype_f5c53620.o \
  $(JUCE_OBJDIR)/s2f~_a3906284.o \
  $(JUCE_OBJDIR)/saw~_a62e6d82.o \
  $(JUCE_OBJDIR)/saw2~_1f7ddcd2.o \
  $(JUCE_OBJDIR)/schmitt~_db394057.o \
  $(JUCE_OBJDIR)/selector_f1d5712c.o \
  $(JUCE_OBJDIR)/separate_d6503f70.o \
  $(JUCE_OBJDIR)/sequencer~_593eed9a.o \
  $(JUCE_OBJDIR)/sh~_d3d33266.o \
  $(JUCE_OBJDIR)/shaper~_eb64924a.o \
  $(JUCE_OBJDIR)/sig2float~_6661a8b0.o \
  $(JUCE_OBJDIR)/sin~_a69b1233.o \
  $(JUCE_OBJDIR)/sine~_2cbcfd2e.o \
  $(JUCE_OBJDIR)/slew~_3164e230.o \
  $(JUCE_OBJDIR)/slew2~_fb15fde4.o \
  $(JUCE_OBJDIR)/slice_3193caef.o \
  $(JUCE_OBJDIR)/sort_a6f14b2b.o \
  $(JUCE_OBJDIR)/spread_e3f53fc0.o \
  $(JUCE_OBJDIR)/spread~_9ab3de88.o \
  $(JUCE_OBJDIR)/square~_9b645e9e.o \
  $(JUCE_OBJDIR)/sr~_d3d7be1c.o \
  $(JUCE_OBJDIR)/standard~_f5bf5afe.o \
  $(JUCE_OBJDIR)/status~_d1a7fba9.o \
  $(JUCE_OBJDIR)/stepnoise~_a0ab317d.o \
  $(JUCE_OBJDIR)/store_3f95ee7e.o \
  $(JUCE_OBJDIR)/susloop~_93c48d76.o \
  $(JUCE_OBJDIR)/suspedal_55aaec96.o \
  $(JUCE_OBJDIR)/svfilter~_832fa160.o \
  $(JUCE_OBJDIR)/symbol2any_7a0a749f.o \
  $(JUCE_OBJDIR)/t2_e5cca1cb.o \
  $(JUCE_OBJDIR)/table~_1770417d.o \
  $(JUCE_OBJDIR)/tabplayer~_24bbd195.o \
  $(JUCE_OBJDIR)/tabwriter~_408b86c3.o \
  $(JUCE_OBJDIR)/tempo~_fe0b6710.o \
  $(JUCE_OBJDIR)/timed.gate~_84066079.o \
  $(JUCE_OBJDIR)/toggleff~_15044347.o \
  $(JUCE_OBJDIR)/touch.in_f2945a41.o \
  $(JUCE_OBJDIR)/touch.out_604faa3c.o \
  $(JUCE_OBJDIR)/tri~_a8cc7880.o \
  $(JUCE_OBJDIR)/trig.delay~_a94b860a.o \
  $(JUCE_OBJDIR)/trig.delay2~_8003d54a.o \
  $(JUCE_OBJDIR)/trigger2_a5c1e407.o \
  $(JUCE_OBJDIR)/trighold~_5834a220.o \
  $(JUCE_OBJDIR)/trunc_71652c89.o \
  $(JUCE_OBJDIR)/trunc~_bb418adf.o \
  $(JUCE_OBJDIR)/unmerge_ebebc95c.o \
  $(JUCE_OBJDIR)/voices_d73cc84e.o \
  $(JUCE_OBJDIR)/vsaw~_dbd12248.o \
  $(JUCE_OBJDIR)/vu~_d40361bc.o \
  $(JUCE_OBJDIR)/wavetable~_ac37f76.o \
  $(JUCE_OBJDIR)/wrap2_efe3905.o \
  $(JUCE_OBJDIR)/wrap2~_d0ca0de3.o \
  $(JUCE_OBJDIR)/wt~_d41104de.o \
  $(JUCE_OBJDIR)/xfade~_bd4e8897.o \
  $(JUCE_OBJDIR)/xgate~_f3163be8.o \
  $(JUCE_OBJDIR)/xgate2~_6f8fdb2c.o \
  $(JUCE_OBJDIR)/xmod~_3c1d2b11.o \
  $(JUCE_OBJDIR)/xmod2~_4766d123.o \
  $(JUCE_OBJDIR)/xselect~_70a2b217.o \
  $(JUCE_OBJDIR)/xselect2~_a3922add.o \
  $(JUCE_OBJDIR)/zerocross~_22dfc273.o \
  $(JUCE_OBJDIR)/PdInstance_c9d7d554.o \
  $(JUCE_OBJDIR)/PdPatch_2b25dab3.o \
  $(JUCE_OBJDIR)/PdGui_34dd0fa6.o \
  $(JUCE_OBJDIR)/PdArray_f4d0bc44.o \
  $(JUCE_OBJDIR)/PdObject_2fcb197e.o \
  $(JUCE_OBJDIR)/x_libpd_multi_a98b54cb.o \
  $(JUCE_OBJDIR)/x_libpd_extra_utils_b8efa354.o \
  $(JUCE_OBJDIR)/BinaryData_ce4232d4.o \
  $(JUCE_OBJDIR)/include_juce_audio_basics_8a4e984a.o \
  $(JUCE_OBJDIR)/include_juce_audio_plugin_client_utils_e32edaee.o \
  $(JUCE_OBJDIR)/include_juce_audio_processors_10c03666.o \
  $(JUCE_OBJDIR)/include_juce_core_f26d17db.o \
  $(JUCE_OBJDIR)/include_juce_data_structures_7471b1e3.o \
  $(JUCE_OBJDIR)/include_juce_events_fd7d695.o \
  $(JUCE_OBJDIR)/include_juce_graphics_f817e147.o \
  $(JUCE_OBJDIR)/include_juce_gui_basics_e3f79785.o \
  $(JUCE_OBJDIR)/include_juce_gui_extra_6dee1c1a.o \

.PHONY: clean all strip VST3

all : VST3

VST3 : $(JUCE_OUTDIR)/$(JUCE_TARGET_VST3)


$(JUCE_OUTDIR)/$(JUCE_TARGET_VST3) : $(OBJECTS_VST3) $(RESOURCES) $(JUCE_OUTDIR)/$(JUCE_TARGET_SHARED_CODE)
	@command -v pkg-config >/dev/null 2>&1 || { echo >&2 "pkg-config not installed. Please, install it."; exit 1; }
	@pkg-config --print-errors freetype2
	@echo Linking "Camomile - VST3"
	-$(V_AT)mkdir -p $(JUCE_BINDIR)
	-$(V_AT)mkdir -p $(JUCE_LIBDIR)
	-$(V_AT)mkdir -p $(JUCE_OUTDIR)
	-$(V_AT)mkdir -p $(JUCE_OUTDIR)/$(JUCE_VST3DIR)/$(JUCE_VST3SUBDIR)
	$(V_AT)$(CXX) -o $(JUCE_OUTDIR)/$(JUCE_TARGET_VST3) $(OBJECTS_VST3) $(JUCE_OUTDIR)/$(JUCE_TARGET_SHARED_CODE) $(JUCE_LDFLAGS) $(JUCE_LDFLAGS_VST3) $(RESOURCES) $(TARGET_ARCH)
	-$(V_AT)mkdir -p $(JUCE_VST3DESTDIR)
	-$(V_AT)cp -R $(JUCE_COPYCMD_VST3)

$(JUCE_OUTDIR)/$(JUCE_TARGET_SHARED_CODE) : $(OBJECTS_SHARED_CODE) $(RESOURCES)
	@command -v pkg-config >/dev/null 2>&1 || { echo >&2 "pkg-config not installed. Please, install it."; exit 1; }
	@pkg-config --print-errors freetype2
	@echo Linking "Camomile - Shared Code"
	-$(V_AT)mkdir -p $(JUCE_BINDIR)
	-$(V_AT)mkdir -p $(JUCE_LIBDIR)
	-$(V_AT)mkdir -p $(JUCE_OUTDIR)
	$(V_AT)$(AR) -rcs $(JUCE_OUTDIR)/$(JUCE_TARGET_SHARED_CODE) $(OBJECTS_SHARED_CODE)

$(JUCE_OBJDIR)/include_juce_audio_plugin_client_VST3_dd633589.o: ../../JuceLibraryCode/include_juce_audio_plugin_client_VST3.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_audio_plugin_client_VST3.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_VST3) $(JUCE_CFLAGS_VST3) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginProcessor_319d19ef.o: ../../../Source/PluginProcessor.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginProcessor.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginProcessorBuses_ff06f3c9.o: ../../../Source/PluginProcessorBuses.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginProcessorBuses.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginProcessorReceive_8862f77e.o: ../../../Source/PluginProcessorReceive.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginProcessorReceive.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginEditor_ef07f2fa.o: ../../../Source/PluginEditor.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginEditor.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginEditorComponents_6d39f4f0.o: ../../../Source/PluginEditorComponents.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginEditorComponents.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginEditorConsole_207d0487.o: ../../../Source/PluginEditorConsole.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginEditorConsole.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginEditorInteraction_f8a5a242.o: ../../../Source/PluginEditorInteraction.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginEditorInteraction.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginEditorObject_7e10b319.o: ../../../Source/PluginEditorObject.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginEditorObject.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginEnvironment_564e0cf0.o: ../../../Source/PluginEnvironment.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginEnvironment.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginParameter_9c951d86.o: ../../../Source/PluginParameter.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginParameter.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginParser_125664ac.o: ../../../Source/PluginParser.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginParser.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PluginLookAndFeel_1523addb.o: ../../../Source/PluginLookAndFeel.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PluginLookAndFeel.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/buffer_e0c59c87.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/shared/buffer.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling buffer.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/file_ee2b0b43.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/shared/file.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling file.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/grow_f060581a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/shared/grow.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling grow.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/magic_3b9753d0.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/shared/magic.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling magic.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/mifi_fa1a4c66.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/shared/mifi.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling mifi.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/random_4a6ad84a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/shared/random.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling random.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/s_utf8_554e14c4.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/shared/s_utf8.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling s_utf8.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/above~_ad5c134e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/above~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling above~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/add~_8798d5ca.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/add~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling add~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/adsr~_6c50f5d9.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/adsr~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling adsr~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/allpass.2nd~_611507df.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/allpass.2nd~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling allpass.2nd~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/allpass.rev~_cdd48ac4.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/allpass.rev~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling allpass.rev~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/args_885f52aa.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/args.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling args.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/asr~_8872938b.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/asr~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling asr~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/autofade~_43f14650.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/autofade~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling autofade~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/autofade2~_3a161dc4.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/autofade2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling autofade2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/balance~_a61ba5af.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/balance~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling balance~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/bandpass~_e4a9a955.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/bandpass~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling bandpass~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/bandstop~_a38eb3c4.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/bandstop~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling bandstop~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/bend.in_73612757.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/bend.in.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling bend.in.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/bend.out_f91c7fe6.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/bend.out.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling bend.out.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/bicoeff_e2cc2f6f.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/bicoeff.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling bicoeff.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/biquads~_5b8713c6.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/biquads~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling biquads~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/blocksize~_1676733d.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/blocksize~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling blocksize~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/break_b84dbf1c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/break.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling break.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/brown~_63b32315.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/brown~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling brown~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/buffer_obj_c2dea585.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/buffer_obj.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling buffer_obj.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/button_ac401bf.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/button.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling button.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.active_b1e71739.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.active.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.active.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.bounds_96865f28.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.bounds.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.bounds.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.edit_bf1f2cbd.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.edit.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.edit.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.gop_509e217f.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.gop.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.gop.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.mouse_df6701dc.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.mouse.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.mouse.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.name_ce521cfe.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.name.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.name.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.pos_511d004b.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.pos.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.pos.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.setname_cef2b0a4.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.setname.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.setname.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.vis_516ed317.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.vis.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.vis.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.wname_ed93e979.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.wname.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.wname.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/canvas.zoom_e3929446.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/canvas.zoom.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling canvas.zoom.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ceil_8b12a0d2.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ceil.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ceil.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ceil~_d7429fb6.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ceil~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ceil~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/cents2ratio_92c0981.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/cents2ratio.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling cents2ratio.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/cents2ratio~_1c564ce7.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/cents2ratio~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling cents2ratio~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/chance_a22df541.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/chance.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling chance.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/chance~_a391d927.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/chance~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling chance~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/changed_a3c9d591.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/changed.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling changed.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/changed~_d57202d7.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/changed~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling changed~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/changed2~_d8acf21d.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/changed2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling changed2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/click_e3302d65.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/click.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling click.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/clipnoise~_4f910a01.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/clipnoise~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling clipnoise~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/cmul~_e5927eba.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/cmul~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling cmul~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/coin_8b9f935e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/coin.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling coin.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/coin~_e853feaa.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/coin~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling coin~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/colors_2754007d.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/colors.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling colors.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/comb.filt~_eee7b4b3.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/comb.filt~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling comb.filt~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/comb.rev~_ea6ef2e5.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/comb.rev~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling comb.rev~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/common.div_f012f19b.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/common.div.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling common.div.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/cosine~_2afd0542.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/cosine~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling cosine~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/crackle~_61704878.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/crackle~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling crackle~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/crossover~_6048ae77.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/crossover~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling crossover~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ctl.in_2c3b06e5.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ctl.in.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ctl.in.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ctl.out_5b7e9218.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ctl.out.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ctl.out.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/cusp~_f31ee62c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/cusp~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling cusp~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/decay~_6e194e11.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/decay~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling decay~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/decay2~_54ef0e23.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/decay2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling decay2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/default_f38399de.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/default.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling default.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/del~_8cc91a20.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/del~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling del~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/detect~_ddf45b58.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/detect~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling detect~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dir_d300192a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/dir.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dir.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dollsym_5263ac79.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/dollsym.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dollsym.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/downsample~_e9ef988f.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/downsample~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling downsample~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/drive~_29263a41.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/drive~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling drive~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dust~_2806f2e9.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/dust~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dust~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/dust2~_d8b6044b.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/dust2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling dust2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/else_8ee36806.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/else.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling else.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/envgen~_8672fab8.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/envgen~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling envgen~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/eq~_d31200af.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/eq~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling eq~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/f2s~_8d674b44.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/f2s~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling f2s~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/factor_6b49c09c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/factor.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling factor.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fader~_6c2cc2d5.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/fader~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fader~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fbdelay~_9c989664.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/fbdelay~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fbdelay~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fbsine~_a15b0af2.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/fbsine~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fbsine~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fbsine2~_89e4ed62.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/fbsine2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fbsine2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fdn.rev~_80ea8ec6.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/fdn.rev~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fdn.rev~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ffdelay~_edaa5268.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ffdelay~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ffdelay~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/float2bits_384edf69.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/float2bits.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling float2bits.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/float2sig~_554b8270.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/float2sig~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling float2sig~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/floor_823cfae9.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/floor.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling floor.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/floor~_c563887f.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/floor~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling floor~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fold_90bf54ce.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/fold.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fold.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fold~_872c6b3a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/fold~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fold~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/fontsize_58be31dd.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/fontsize.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling fontsize.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/format_6910b544.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/format.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling format.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/freq.shift~_8576c3cf.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/freq.shift~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling freq.shift~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/function_50bed6e5.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/function.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling function.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/function~_c71d2c03.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/function~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling function~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/gate2imp~_ec2b6f16.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/gate2imp~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling gate2imp~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/gaussian~_9c8b5b00.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/gaussian~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling gaussian~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/gbman~_1815990c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/gbman~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling gbman~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/gcd_d32770e5.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/gcd.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling gcd.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/giga.rev~_a2cd504a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/giga.rev~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling giga.rev~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/glide~_2266b646.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/glide~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling glide~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/glide2~_2a4eac8e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/glide2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling glide2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/gray~_c09fb998.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/gray~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling gray~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/gui_d32fb258.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/gui.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling gui.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/henon~_2123995b.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/henon~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling henon~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/highpass~_95f70d48.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/highpass~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling highpass~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/highshelf~_ba898143.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/highshelf~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling highshelf~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/hot_d33b38ea.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/hot.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling hot.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/hz2rad_11c7ac82.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/hz2rad.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling hz2rad.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/hz2rad~_272f0a06.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/hz2rad~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling hz2rad~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ikeda~_b66da0cb.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ikeda~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ikeda~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/imp~_95c3e2bf.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/imp~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling imp~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/imp2~_22970f35.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/imp2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling imp2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/impseq~_46b9aae8.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/impseq~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling impseq~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/impulse~_64c0cf6.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/impulse~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling impulse~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/impulse2~_c3142bde.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/impulse2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling impulse2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/initmess_8f77ca15.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/initmess.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling initmess.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/int~_95d3cbbc.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/int~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling int~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/keyboard_ab60f34.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/keyboard.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling keyboard.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lag~_9a353b39.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lag~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lag~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lag2~_ac50c5fb.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lag2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lag2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lastvalue~_6a993590.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lastvalue~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lastvalue~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/latoocarfian~_16cea356.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/latoocarfian~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling latoocarfian~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lb_e5c9b303.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lb.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lb.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lfnoise~_c303102b.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lfnoise~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lfnoise~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/limit_ba64f2d8.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/limit.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling limit.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lincong~_efd1d15.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lincong~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lincong~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/loadbanger_2b6d198.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/loadbanger.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling loadbanger.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/logistic~_c9ae407b.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/logistic~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling logistic~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/loop_9afdf2b1.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/loop.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling loop.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lorenz~_25b4da59.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lorenz~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lorenz~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lowpass~_c79b5e86.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lowpass~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lowpass~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/lowshelf~_bd6f57c5.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/lowshelf~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling lowshelf~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/match~_5e81cc26.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/match~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling match~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/median~_ccad0791.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/median~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling median~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/merge_e8bd2015.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/merge.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling merge.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/message_f7376a24.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/message.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling message.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/messbox_f7496bf0.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/messbox.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling messbox.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/midi_9c5923ee.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/midi.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling midi.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/mouse_f9fd5142.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/mouse.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling mouse.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/mov.avg~_b0cd2e13.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/mov.avg~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling mov.avg~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/mov.rms~_cd56318d.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/mov.rms~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling mov.rms~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/mtx~_9cfd8cba.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/mtx~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling mtx~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/nbang_17987803.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/nbang.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling nbang.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/note_9e69c07f.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/note.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling note.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/note.in_b47c583e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/note.in.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling note.in.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/note.out_db676bdf.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/note.out.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling note.out.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/nyquist~_21b9eb30.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/nyquist~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling nyquist~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/op~_d39e775a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/op~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling op~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/openfile_89124653.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/openfile.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling openfile.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/oscilloscope_50ce455c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/oscilloscope.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling oscilloscope.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/oscilloscope_dialog_f88af155.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/oscilloscope_dialog.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling oscilloscope_dialog.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pack2_7fca20d6.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pack2.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pack2.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pad_d3a55bb0.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pad.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pad.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pan2~_804c5786.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pan2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pan2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pan4~_804d4044.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pan4~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pan4~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/panic_8064f294.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/panic.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling panic.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/parabolic~_5a57d632.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/parabolic~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling parabolic~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/peak~_8682719c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/peak~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling peak~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pgm.in_c4ae248a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pgm.in.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pgm.in.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pgm.out_d16f2913.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pgm.out.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pgm.out.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pic_d3a8fae7.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pic.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pic.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pimp~_8e0133ff.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pimp~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pimp~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pimpmul~_24edf023.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pimpmul~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pimpmul~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pinknoise~_d5016227.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pinknoise~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pinknoise~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pluck~_ddc0144a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pluck~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pluck~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pmosc~_94710e9.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pmosc~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pmosc~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/power~_7ffbd4e6.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/power~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling power~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/properties_f4ab9f80.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/properties.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling properties.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pulse~_ab5b49d2.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pulse~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pulse~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pulsecount~_cc554805.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pulsecount~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pulsecount~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/pulsediv~_cb3f7983.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/pulsediv~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling pulsediv~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/quad~_d6b30834.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/quad~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling quad~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/quantizer_1cbae2fe.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/quantizer.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling quantizer.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/quantizer~_7aa2a30a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/quantizer~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling quantizer~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rad2hz_47e793dc.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rad2hz.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rad2hz.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rad2hz~_b50c0dec.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rad2hz~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rad2hz~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ramp~_ea26e589.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ramp~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ramp~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rampnoise~_2e4bd0c3.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rampnoise~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rampnoise~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rand.f_5b9df8aa.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rand.f.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rand.f.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rand.f~_182242de.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rand.f~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rand.f~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rand.i_5b9e03ed.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rand.i.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rand.i.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rand.i~_18239ffb.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rand.i~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rand.i~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rand.seq_ecd2e2a3.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rand.seq.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rand.seq.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/randpulse~_41a654f7.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/randpulse~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling randpulse~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/randpulse2~_f302e3fd.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/randpulse2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling randpulse2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/range~_5be199ae.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/range~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling range~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ratio2cents_7e3bd981.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ratio2cents.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ratio2cents.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/ratio2cents~_49407ce7.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/ratio2cents~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling ratio2cents~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rec_d3c3586d.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rec.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rec.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/receiver_60f6233c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/receiver.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling receiver.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rescale_c1425114.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rescale.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rescale.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rescale~_6708f7b4.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rescale~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rescale~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/resonant~_f60b3ad3.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/resonant~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling resonant~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/resonant2~_cb3ab9a1.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/resonant2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling resonant2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/retrieve_f5b31a49.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/retrieve.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling retrieve.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rint_a4e6140a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rint.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rint.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rint~_f7dd937e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rint~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rint~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rms~_a520dd73.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rms~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rms~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/rotate~_29389a0.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/rotate~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling rotate~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/routeall_8afce1c5.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/routeall.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling routeall.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/router_4d21c816.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/router.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling router.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/routetype_f5c53620.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/routetype.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling routetype.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/s2f~_a3906284.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/s2f~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling s2f~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/saw~_a62e6d82.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/saw~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling saw~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/saw2~_1f7ddcd2.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/saw2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling saw2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/schmitt~_db394057.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/schmitt~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling schmitt~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/selector_f1d5712c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/selector.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling selector.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/separate_d6503f70.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/separate.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling separate.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/sequencer~_593eed9a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/sequencer~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling sequencer~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/sh~_d3d33266.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/sh~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling sh~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/shaper~_eb64924a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/shaper~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling shaper~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/sig2float~_6661a8b0.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/sig2float~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling sig2float~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/sin~_a69b1233.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/sin~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling sin~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/sine~_2cbcfd2e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/sine~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling sine~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/slew~_3164e230.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/slew~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling slew~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/slew2~_fb15fde4.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/slew2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling slew2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/slice_3193caef.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/slice.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling slice.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/sort_a6f14b2b.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/sort.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling sort.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/spread_e3f53fc0.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/spread.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling spread.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/spread~_9ab3de88.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/spread~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling spread~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/square~_9b645e9e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/square~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling square~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/sr~_d3d7be1c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/sr~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling sr~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/standard~_f5bf5afe.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/standard~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling standard~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/status~_d1a7fba9.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/status~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling status~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/stepnoise~_a0ab317d.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/stepnoise~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling stepnoise~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/store_3f95ee7e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/store.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling store.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/susloop~_93c48d76.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/susloop~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling susloop~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/suspedal_55aaec96.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/suspedal.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling suspedal.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/svfilter~_832fa160.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/svfilter~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling svfilter~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/symbol2any_7a0a749f.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/symbol2any.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling symbol2any.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/t2_e5cca1cb.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/t2.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling t2.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/table~_1770417d.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/table~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling table~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tabplayer~_24bbd195.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/tabplayer~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tabplayer~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tabwriter~_408b86c3.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/tabwriter~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tabwriter~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tempo~_fe0b6710.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/tempo~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tempo~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/timed.gate~_84066079.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/timed.gate~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling timed.gate~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/toggleff~_15044347.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/toggleff~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling toggleff~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/touch.in_f2945a41.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/touch.in.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling touch.in.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/touch.out_604faa3c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/touch.out.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling touch.out.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/tri~_a8cc7880.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/tri~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling tri~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/trig.delay~_a94b860a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/trig.delay~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling trig.delay~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/trig.delay2~_8003d54a.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/trig.delay2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling trig.delay2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/trigger2_a5c1e407.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/trigger2.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling trigger2.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/trighold~_5834a220.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/trighold~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling trighold~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/trunc_71652c89.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/trunc.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling trunc.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/trunc~_bb418adf.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/trunc~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling trunc~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/unmerge_ebebc95c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/unmerge.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling unmerge.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/voices_d73cc84e.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/voices.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling voices.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/vsaw~_dbd12248.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/vsaw~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling vsaw~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/vu~_d40361bc.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/vu~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling vu~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/wavetable~_ac37f76.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/wavetable~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling wavetable~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/wrap2_efe3905.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/wrap2.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling wrap2.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/wrap2~_d0ca0de3.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/wrap2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling wrap2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/wt~_d41104de.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/wt~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling wt~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/xfade~_bd4e8897.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/xfade~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling xfade~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/xgate~_f3163be8.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/xgate~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling xgate~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/xgate2~_6f8fdb2c.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/xgate2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling xgate2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/xmod~_3c1d2b11.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/xmod~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling xmod~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/xmod2~_4766d123.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/xmod2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling xmod2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/xselect~_70a2b217.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/xselect~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling xselect~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/xselect2~_a3922add.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/xselect2~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling xselect2~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/zerocross~_22dfc273.o: ../../../../TESTE_de_compilação/Camomile-ELSE/Source/Pd/ELSE/zerocross~.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling zerocross~.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PdInstance_c9d7d554.o: ../../../Source/Pd/PdInstance.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PdInstance.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PdPatch_2b25dab3.o: ../../../Source/Pd/PdPatch.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PdPatch.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PdGui_34dd0fa6.o: ../../../Source/Pd/PdGui.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PdGui.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PdArray_f4d0bc44.o: ../../../Source/Pd/PdArray.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PdArray.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/PdObject_2fcb197e.o: ../../../Source/Pd/PdObject.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling PdObject.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/x_libpd_multi_a98b54cb.o: ../../../Source/Pd/x_libpd_multi.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling x_libpd_multi.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/x_libpd_extra_utils_b8efa354.o: ../../../Source/Pd/x_libpd_extra_utils.c
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling x_libpd_extra_utils.c"
	$(V_AT)$(CC) $(JUCE_CFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/BinaryData_ce4232d4.o: ../../JuceLibraryCode/BinaryData.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling BinaryData.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_audio_basics_8a4e984a.o: ../../JuceLibraryCode/include_juce_audio_basics.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_audio_basics.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_audio_plugin_client_utils_e32edaee.o: ../../JuceLibraryCode/include_juce_audio_plugin_client_utils.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_audio_plugin_client_utils.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_audio_processors_10c03666.o: ../../JuceLibraryCode/include_juce_audio_processors.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_audio_processors.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_core_f26d17db.o: ../../JuceLibraryCode/include_juce_core.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_core.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_data_structures_7471b1e3.o: ../../JuceLibraryCode/include_juce_data_structures.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_data_structures.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_events_fd7d695.o: ../../JuceLibraryCode/include_juce_events.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_events.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_graphics_f817e147.o: ../../JuceLibraryCode/include_juce_graphics.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_graphics.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_gui_basics_e3f79785.o: ../../JuceLibraryCode/include_juce_gui_basics.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_gui_basics.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

$(JUCE_OBJDIR)/include_juce_gui_extra_6dee1c1a.o: ../../JuceLibraryCode/include_juce_gui_extra.cpp
	-$(V_AT)mkdir -p $(JUCE_OBJDIR)
	@echo "Compiling include_juce_gui_extra.cpp"
	$(V_AT)$(CXX) $(JUCE_CXXFLAGS) $(JUCE_CPPFLAGS_SHARED_CODE) $(JUCE_CFLAGS_SHARED_CODE) -o "$@" -c "$<"

clean:
	@echo Cleaning Camomile
	$(V_AT)$(CLEANCMD)

strip:
	@echo Stripping Camomile
	-$(V_AT)$(STRIP) --strip-unneeded $(JUCE_OUTDIR)/$(TARGET)

-include $(OBJECTS_VST3:%.o=%.d)
-include $(OBJECTS_SHARED_CODE:%.o=%.d)

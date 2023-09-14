
obj-y	+= libata.o

# non-SFF interface
obj-y	+= ahci.o libahci.o
obj-y	+= acard-ahci.o libahci.o
obj-y	+= ahci_platform.o libahci.o libahci_platform.o
obj-y	+= sata_fsl.o
obj-y	+= sata_inic162x.o
obj-y	+= sata_sil24.o
obj-y	+= sata_dwc_460ex.o
obj-y	+= sata_highbank.o libahci.o
obj-y	+= ahci_brcmstb.o libahci.o libahci_platform.o
obj-y	+= ahci_ceva.o libahci.o libahci_platform.o
obj-y	+= ahci_da850.o libahci.o libahci_platform.o
obj-y	+= ahci_imx.o libahci.o libahci_platform.o
obj-y	+= ahci_mvebu.o libahci.o libahci_platform.o
obj-y	+= ahci_sunxi.o libahci.o libahci_platform.o
obj-y	+= ahci_st.o libahci.o libahci_platform.o
obj-y	+= ahci_tegra.o libahci.o libahci_platform.o
obj-y	+= ahci_xgene.o libahci.o libahci_platform.o
obj-y	+= ahci_qoriq.o libahci.o libahci_platform.o
obj-y	+= ahci_rtk.o libahci.o libahci_platform.o
obj-y	+= ahci_rtk_1619.o libahci.o libahci_platform.o

# SFF w/ custom DMA
obj-y	+= pdc_adma.o
obj-y	+= pata_arasan_cf.o
obj-y	+= pata_octeon_cf.o
obj-y	+= sata_qstor.o
obj-y	+= sata_sx4.o
obj-y	+= ata_syno_i2c.o

# SFF SATA w/ BMDMA
obj-m	+= ata_piix.o
obj-y	+= sata_mv.o
obj-m	+= sata_nv.o
obj-y	+= sata_promise.o
obj-y	+= sata_rcar.o
obj-m	+= sata_sil.o
obj-y	+= sata_sis.o
obj-y	+= sata_svw.o
obj-y	+= sata_uli.o
obj-y	+= sata_via.o
obj-y	+= sata_vsc.o

# SFF PATA w/ BMDMA
obj-y	+= pata_ali.o
obj-y	+= pata_amd.o
obj-y	+= pata_artop.o
obj-y	+= pata_atiixp.o
obj-y	+= pata_atp867x.o
obj-y	+= pata_bf54x.o
obj-y	+= pata_cmd64x.o
obj-y	+= pata_cs5520.o
obj-y	+= pata_cs5530.o
obj-y	+= pata_cs5535.o
obj-y	+= pata_cs5536.o
obj-y	+= pata_cypress.o
obj-y	+= pata_efar.o
obj-y	+= pata_ep93xx.o
obj-y	+= pata_hpt366.o
obj-y	+= pata_hpt37x.o
obj-y	+= pata_hpt3x2n.o
obj-y	+= pata_hpt3x3.o
obj-y	+= pata_icside.o
obj-y	+= pata_imx.o
obj-y	+= pata_it8213.o
obj-y	+= pata_it821x.o
obj-y	+= pata_jmicron.o
obj-y	+= pata_macio.o
obj-y	+= pata_marvell.o
obj-y	+= pata_mpc52xx.o
obj-y	+= pata_netcell.o
obj-y	+= pata_ninja32.o
obj-y	+= pata_ns87415.o
obj-y	+= pata_oldpiix.o
obj-y	+= pata_optidma.o
obj-y	+= pata_pdc2027x.o
obj-y	+= pata_pdc202xx_old.o
obj-y	+= pata_radisys.o
obj-y	+= pata_rdc.o
obj-y	+= pata_sc1200.o
obj-y	+= pata_sch.o
obj-y	+= pata_serverworks.o
obj-y	+= pata_sil680.o
obj-y	+= pata_sis.o
obj-y	+= pata_piccolo.o
obj-y	+= pata_triflex.o
obj-y	+= pata_via.o
obj-y	+= pata_sl82c105.o

# SFF PIO only
obj-y	+= pata_at32.o
obj-y	+= pata_at91.o
obj-y	+= pata_cmd640.o
obj-y	+= pata_isapnp.o
obj-y	+= pata_ixp4xx_cf.o
obj-y	+= pata_mpiix.o
obj-y	+= pata_ns87410.o
obj-y	+= pata_opti.o
obj-y	+= pata_pcmcia.o
obj-y	+= pata_palmld.o
obj-y	+= pata_platform.o
obj-y	+= pata_of_platform.o
obj-y	+= pata_rb532_cf.o
obj-y	+= pata_rz1000.o
obj-y	+= pata_samsung_cf.o

obj-y	+= pata_pxa.o

# Should be last but two libata driver
obj-y	+= pata_acpi.o
# Should be last but one libata driver
obj-y	+= ata_generic.o
# Should be last libata driver
obj-y	+= pata_legacy.o

libata-y	:= libata-core.o libata-scsi.o libata-eh.o \
	libata-transport.o libata-trace.o
libata-y	+= libata-sff.o
libata-y	+= libata-pmp.o
libata-y	+= libata-acpi.o
libata-y	+= libata-zpodd.o

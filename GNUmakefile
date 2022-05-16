include /ioc/tools/driver.makefile

# build for EPICS_Version >=7 only
EXCLUDE_VERSIONS = 3

BUILDCLASSES = Linux

# build only for Debian10
ARCH_FILTER = deb10%

# iocsh
# SCRIPTS += $(wildcard iocsh/*.iocsh)

# config
# SCRIPTS += $(wildcard cfg/*.yaml)

# templates
TEMPLATES+=$(wildcard ./db/*.db)
TEMPLATES+=$(wildcard ./db/*.template)
TEMPLATES+=$(wildcard ./db/*.substitutions)
TEMPLATES+=$(wildcard ./db/*.subs)

# stream protocols
SCRIPTS+=$(wildcard ./cfg/*.ptcols)

# startup script
SCRIPTS+=./startup.cmd


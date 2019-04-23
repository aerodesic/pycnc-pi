# pycnc-pi
yocto top-level project for a pycnc-based (with rt kernel) yocto build

Create a top-level working folder and check this project:

  mkdir Top-Level-Project
  cd Top-Level-Project
  git clone https://github.com/aerodesic/pycnc-pi
  ./pycnc-pi/get_files.sh
  source poke/oe-init-build-env pycnc-pi
  bitbake pycnc-image

  At end, you will have a pycnc-image (sdimg) ready to copy to a microsd.



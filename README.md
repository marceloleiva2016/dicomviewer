[![Build Status](https://github.com/ayselafsar/dicomviewer/workflows/Build/badge.svg)](https://github.com/ayselafsar/dicomviewer/actions?workflow=Build)
[![Downloads](https://img.shields.io/github/downloads/ayselafsar/dicomviewer/total.svg)](https://github.com/ayselafsar/dicomviewer/releases)

# DICOM Viewer

It is a DICOM viewer which uses [cornerstonejs](https://github.com/cornerstonejs) library to display DICOM files in Nextcloud.

For more information, see the blog post [Nextcloud in Digital Imaging](https://nextcloud.com/blog/digital-imaging-for-medicine-in-nextcloud/)


<kbd>![Viewer 1](https://github.com/ayselafsar/dicomviewer/blob/master/screenshots/viewer1.png)  </kbd>
<kbd>![Viewer 2](https://github.com/ayselafsar/dicomviewer/blob/master/screenshots/viewer2.png)  </kbd>
<kbd>![Viewer 3](https://github.com/ayselafsar/dicomviewer/blob/master/screenshots/viewer3.png)  </kbd>
<kbd>![Viewer 4](https://github.com/ayselafsar/dicomviewer/blob/master/screenshots/viewer4.png)  </kbd>
<kbd>![Dump 1](https://github.com/ayselafsar/dicomviewer/blob/master/screenshots/dump1.png)  </kbd>
<kbd>![Dump 2](https://github.com/ayselafsar/dicomviewer/blob/master/screenshots/dump2.png)  </kbd>


### Features

* **Viewer:** A DICOM viewer which displays images grouped by study and series in selected folders and allows to manipulate images with imaging tools.
* **DICOM Dump:** A list of DICOM attributes displayed on the sidebar with image thumbnail.
* **Translation:** The ability to use localized languages. Translators are encouraged to contribute.


### Quick Start

On your Nextcloud, simply navigate to Apps > Multimedia > DICOM Viewer, and enable it.


### Development

#### Pre-requisites

- make
- [NodeJS](https://nodejs.org)
- [Nextcloud Server](https://nextcloud.com/install/#instructions-server)
  * Docker options including docker-compose is [here](https://github.com/nextcloud/docker) and Docker images are [here](https://hub.docker.com/_/nextcloud/)
  * You can easily find VM and other options [here](https://nextcloud.com)

#### Build

You can build the source code with the following steps:

1. Clone this repository on `path-to-nextcloud/apps`

2. Change into the directory you have cloned this repository

3. Run `make` command to build source code

4. Enable the DICOM Viewer app in Nextcloud

### Sponsors

Thanks to our all contributors and sponsors!

<table>
  <tr>
    <td><a href="https://nextcloud.com"><img src="https://user-images.githubusercontent.com/8215016/70382026-f51b2200-1922-11ea-9121-6bbbb9fb2a6f.png" height="50px;" alt="Nextcloud"/></td>
  </tr>
</table>

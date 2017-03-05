# Windows Server: 将虚机从阿里云迁移到Azure

阿里云无法像Azure一样，能容易的导出vhd并迁移到各种环境中，包含本地及云端环境，或是迁移至其他的区域。这造成在开发，测试或是扩展时有很大的麻烦。因此本文阐述的是如何将Windows Server的虚机，从阿里云中迁移到Azure环境，同时能保存虚机内的数据，不需重新部署应用的方法。
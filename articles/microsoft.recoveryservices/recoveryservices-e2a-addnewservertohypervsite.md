<properties
    pageTitle="Site Recovery (VMM to Azure)/Site Recovery provider setup and registration"
    description="站点恢复（VMM 到 Azure）/站点恢复提供程序的安装和注册"
    service="microsoft.recoveryservices"
    resource="vaults"
    authors="anoopkv"
    displayOrder=""
    selfHelpType="generic"
    supportTopicIds="32536453"
    resourceTags=""
    productPesIds="15207"
    cloudEnvironments="public"
/>


# <a name="site-recovery-vmm-to-azuresite-recovery-provider-setup-and-registration"></a>站点恢复（VMM 到 Azure）/站点恢复提供程序的安装和注册

将服务器添加到 Hyper-V 站点时出现的常见问题

## <a name="recommended-steps"></a>**建议的步骤**

*  确保在服务器上使用身份为**本地管理员**的帐户进行安装。
* 确保安装 **Microsoft Azure Site Recovery 提供程序**的服务器有权访问以下 URL <br>
    1. *.hypervrecoverymanager.windowsazure.com
    2. *.accesscontrol.windows.net
    3. *.backup.windowsazure.com
    4. *.blob.core.windows.net
    5. *.store.core.windows.net

* 确保安装 **Microsoft Azure Site Recovery 提供程序**的服务器上的时钟已根据其目标时区设置了正确的时间。

* 如果你知道要安装 **Microsoft Azure Site Recovery 提供程序**的服务器在代理服务器后面，请始终选择“使用代理服务器连接到 Azure Site Recovery”选项。

## <a name="recommended-documents"></a>**建议的文档**
[本地先决条件](https://azure.microsoft.com/documentation/articles/site-recovery-vmm-to-azure/#on-premises-prerequisites)



<!--HONumber=Nov16_HO4-->



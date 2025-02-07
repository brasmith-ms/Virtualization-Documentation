# [Overview](./index.md)

# [Hyper-V WMI provider](https://docs.microsoft.com/windows/win32/hyperv_v2/windows-virtualization-portal)

# Host Compute System API
## [Overview](./hcs/overview.md)
## API Reference
### [Overview](./hcs/Reference/APIOverview.md)
### Data Types
#### [HCS Error Code](./hcs/Reference/HCSHResult.md)
#### [HCS_OPERATION_TYPE](./hcs/Reference/HCS_OPERATION_TYPE.md)
#### [HCS_EVENT_TYPE](./hcs/Reference/HCS_EVENT_TYPE.md)
#### [HCS_EVENT](./hcs/Reference/HCS_EVENT.md)
#### [HCS_EVENT_OPTIONS](./hcs/Reference/HCS_EVENT_OPTIONS.md)
#### [HCS_PROCESS_INFORMATION](./hcs/Reference/HCS_PROCESS_INFORMATION.md)
### Callback Function Types
#### [HCS_OPERATION_COMPLETION](./hcs/Reference/HCS_OPERATION_COMPLETION.md)
#### [HCS_EVENT_CALLBACK](./hcs/Reference/HCS_EVENT_CALLBACK.md)
### Functions
#### Operation
##### [HcsCreateOperation](./hcs/Reference/HcsCreateOperation.md)
##### [HcsCloseOperation](./hcs/Reference/HcsCloseOperation.md)
##### [HcsGetOperationContext](./hcs/Reference/HcsGetOperationContext.md)
##### [HcsSetOperationContext](./hcs/Reference/HcsSetOperationContext.md)
##### [HcsGetComputeSystemFromOperation](./hcs/Reference/HcsGetComputeSystemFromOperation.md)
##### [HcsGetProcessFromOperation](./hcs/Reference/HcsGetProcessFromOperation.md)
##### [HcsGetOperationType](./hcs/Reference/HcsGetOperationType.md)
##### [HcsGetOperationId](./hcs/Reference/HcsGetOperationId.md)
##### [HcsGetOperationResult](./hcs/Reference/HcsGetOperationResult.md)
##### [HcsGetOperationResultAndProcessInfo](./hcs/Reference/HcsGetOperationResultAndProcessInfo.md)
##### [HcsWaitForOperationResult](./hcs/Reference/HcsWaitForOperationResult.md)
##### [HcsWaitForOperationResultAndProcessInfo](./hcs/Reference/HcsWaitForOperationResultAndProcessInfo.md)
##### [HcsSetOperationCallback](./hcs/Reference/HcsSetOperationCallback.md)
##### [HcsCancelOperation](./hcs/Reference/HcsCancelOperation.md)
#### Compute System
##### [HcsCreateComputeSystem](./hcs/Reference/HcsCreateComputeSystem.md)
##### [HcsOpenComputeSystem](./hcs/Reference/HcsOpenComputeSystem.md)
##### [HcsCloseComputeSystem](./hcs/Reference/HcsCloseComputeSystem.md)
##### [HcsStartComputeSystem](./hcs/Reference/HcsStartComputeSystem.md)
##### [HcsShutDownComputeSystem](./hcs/Reference/HcsShutDownComputeSystem.md)
##### [HcsTerminateComputeSystem](./hcs/Reference/HcsTerminateComputeSystem.md)
##### [HcsCrashComputeSystem](./hcs/Reference/HcsCrashComputeSystem.md)
##### [HcsPauseComputeSystem](./hcs/Reference/HcsPauseComputeSystem.md)
##### [HcsResumeComputeSystem](./hcs/Reference/HcsResumeComputeSystem.md)
##### [HcsSaveComputeSystem](./hcs/Reference/HcsSaveComputeSystem.md)
##### [HcsGetComputeSystemProperties](./hcs/Reference/HcsGetComputeSystemProperties.md)
##### [HcsModifyComputeSystem](./hcs/Reference/HcsModifyComputeSystem.md)
##### [HcsSetComputeSystemCallback](./hcs/Reference/HcsSetComputeSystemCallback.md)
##### [HcsEnumerateComputeSystems](./hcs/Reference/HcsEnumerateComputeSystems.md)
#### Process Execution
##### [HcsCreateProcess](./hcs/Reference/HcsCreateProcess.md)
##### [HcsOpenProcess](./hcs/Reference/HcsOpenProcess.md)
##### [HcsCloseProcess](./hcs/Reference/HcsCloseProcess.md)
##### [HcsTerminateProcess](./hcs/Reference/HcsTerminateProcess.md)
##### [HcsSignalProcess](./hcs/Reference/HcsSignalProcess.md)
##### [HcsGetProcessInfo](./hcs/Reference/HcsGetProcessInfo.md)
##### [HcsGetProcessProperties](./hcs/Reference/HcsGetProcessProperties.md)
##### [HcsModifyProcess](./hcs/Reference/HcsModifyProcess.md)
##### [HcsSetProcessCallback](./hcs/Reference/HcsSetProcessCallback.md)
#### Host Service
##### [HcsGetServiceProperties](./hcs/Reference/HcsGetServiceProperties.md)
##### [HcsModifyServiceSettings](./hcs/Reference/HcsModifyServiceSettings.md)
##### [HcsSubmitWerReport](./hcs/Reference/HcsSubmitWerReport.md)
#### Virtual Machine Utilities
##### [HcsCreateEmptyGuestStateFile](./hcs/Reference/HcsCreateEmptyGuestStateFile.md)
##### [HcsCreateEmptyRuntimeStateFile](./hcs/Reference/HcsCreateEmptyRuntimeStateFile.md)
##### [HcsGrantVmAccess](./hcs/Reference/HcsGrantVmAccess.md)
##### [HcsRevokeVmAccess](./hcs/Reference/HcsRevokeVmAccess.md)
##### [HcsGrantVmGroupAccess](./hcs/Reference/HcsGrantVmGroupAccess.md)
##### [HcsRevokeVmGroupAccess](./hcs/Reference/HcsRevokeVmGroupAccess.md)
#### Containers Storage Utilities
##### [HcsImportLayer](./hcs/Reference/HcsImportLayer.md)
##### [HcsExportLayer](./hcs/Reference/HcsExportLayer.md)
##### [HcsExportLegacyWritableLayer](./hcs/Reference/HcsExportLegacyWritableLayer.md)
##### [HcsDestroyLayer](./hcs/Reference/HcsDestroyLayer.md)
##### [HcsSetupBaseOSLayer](./hcs/Reference/HcsSetupBaseOSLayer.md)
##### [HcsInitializeWritableLayer](./hcs/Reference/HcsInitializeWritableLayer.md)
##### [HcsInitializeLegacyWritableLayer](./hcs/Reference/HcsInitializeLegacyWritableLayer.md)
##### [HcsAttachLayerStorageFilter](./hcs/Reference/HcsAttachLayerStorageFilter.md)
##### [HcsDetachLayerStorageFilter](./hcs/Reference/HcsDetachLayerStorageFilter.md)
##### [HcsFormatWritableLayerVhd](./hcs/Reference/HcsFormatWritableLayerVhd.md)
##### [HcsGetLayerVhdMountPath](./hcs/Reference/HcsGetLayerVhdMountPath.md)
## JSON Schema
### [Schema Overview](./hcs/SchemaOverview.md)
### [JSON Schema Reference](./hcs/SchemaReference.md)
### [Schema in Different Languages](./hcs/SchemaSample.md)
## Samples
### [Quick Start](./hcs/Reference/Tutorial.md)
### [Operation Completion](./hcs/Reference/OperationCompletionSample.md)
### [Event Callback](./hcs/Reference/EventCallbackSample.md)
### [Compute System](./hcs/Reference/ComputeSystemSample.md)
### [Host Service](./hcs/Reference/ServiceSample.md)
### [Virtual Machine Utilities](./hcs/Reference/UtilityFunctionSample.md)

# Host Compute Network API
## [Overview](https://docs.microsoft.com/windows-server/networking/technologies/hcn/hcn-top)
### Data Types
#### [HCN Error Codes](./hcn/Reference/HCNHResult.md)
#### [HCN\_NOTIFICATIONS](./hcn/Reference/HCN_NOTIFICATIONS.md)
#### [HCN\_NOTIFICATION_CALLBACK](./hcn/Reference/HCN_NOTIFICATION_CALLBACK.md)
#### [HCN\_CALLBACK](./hcn/Reference/HCN_CALLBACK.md)
#### [HCN\_NAMESPACE](./hcn/Reference/HCN_NAMESPACE.md)
#### [HCN\_ENDPOINT](./hcn/Reference/HCN_ENDPOINT.md)
#### [HCN\_NETWORK](./hcn/Reference/HCN_NETWORK.md)
#### [HCN\_LOADBALANCER](./hcn/Reference/HCN_LOADBALANCER.md)
#### [HCN\_SERVICE](./hcn/Reference/HCN_SERVICE.md)
#### [HCN\_GUESTNETWORKSERVICE](./hcn/Reference/HCN_GUESTNETWORKSERVICE.md)
#### [HCN\_PORT\_PROTOCOL](./hcn/Reference/HCN_PORT_PROTOCOL.md)
#### [HCN\_PORT\_ACCESS](./hcn/Reference/HCN_PORT_ACCESS.md)
#### [HCN\_PORT\_RANGE\_RESERVATION](./hcn/Reference/HCN_PORT_RANGE_RESERVATION.md)
#### [HCN\_PORT\_RANGE\_ENTRY](./hcn/Reference/HCN_PORT_RANGE_ENTRY.md)
### Functions
#### Networks
##### [HcnEnumerateNetworks](./hcn/Reference/HcnEnumerateNetworks.md)
##### [HcnCreateNetwork](./hcn/Reference/HcnCreateNetwork.md)
##### [HcnOpenNetwork](./hcn/Reference/HcnOpenNetwork.md)
##### [HcnModifyNetwork](./hcn/Reference/HcnModifyNetwork.md)
##### [HcnQueryNetworkProperties](./hcn/Reference/HcnQueryNetworkProperties.md)
##### [HcnDeleteNetwork](./hcn/Reference/HcnDeleteNetwork.md)
##### [HcnCloseNetwork](./hcn/Reference/HcnCloseNetwork.md)
#### Namespaces
##### [HcnEnumerateNamespaces](./hcn/Reference/HcnEnumerateNamespaces.md)
##### [HcnCreateNamespace](./hcn/Reference/HcnCreateNamespace.md)
##### [HcnOpenNamespace](./hcn/Reference/HcnOpenNamespace.md)
##### [HcnModifyNamespace](./hcn/Reference/HcnModifyNamespace.md)
##### [HcnQueryNamespaceProperties](./hcn/Reference/HcnQueryNamespaceProperties.md)
##### [HcnDeleteNamespace](./hcn/Reference/HcnDeleteNamespace.md)
##### [HcnCloseNamespace](./hcn/Reference/HcnCloseNamespace.md)
#### Endpoints
##### [HcnEnumerateEndpoints](./hcn/Reference/HcnEnumerateEndpoints.md)
##### [HcnCreateEndpoint](./hcn/Reference/HcnCreateEndpoint.md)
##### [HcnOpenEndpoint](./hcn/Reference/HcnOpenEndpoint.md)
##### [HcnModifyEndpoint](./hcn/Reference/HcnModifyEndpoint.md)
##### [HcnQueryEndpointProperties](./hcn/Reference/HcnQueryEndpointProperties.md)
##### [HcnDeleteEndpoint](./hcn/Reference/HcnDeleteEndpoint.md)
##### [HcnCloseEndpoint](./hcn/Reference/HcnCloseEndpoint.md)
#### LoadBalancers
##### [HcnEnumerateLoadBalancers](./hcn/Reference/HcnEnumerateLoadBalancers.md)
##### [HcnCreateLoadBalancer](./hcn/Reference/HcnCreateLoadBalancer.md)
##### [HcnOpenLoadBalancer](./hcn/Reference/HcnOpenLoadBalancer.md)
##### [HcnModifyLoadBalancer](./hcn/Reference/HcnModifyLoadBalancer.md)
##### [HcnQueryLoadBalancerProperties](./hcn/Reference/HcnQueryLoadBalancerProperties.md)
##### [HcnDeleteLoadBalancer](./hcn/Reference/HcnDeleteLoadBalancer.md)
##### [HcnCloseLoadBalancer](./hcn/Reference/HcnCloseLoadBalancer.md)
#### Services
##### [HcnRegisterServiceCallback](./hcn/Reference/HcnRegisterServiceCallback.md)
##### [HcnUnregisterServiceCallback](./hcn/Reference/HcnUnregisterServiceCallback.md)
#### Guest Network Services
##### [HcnRegisterGuestNetworkServiceCallback](./hcn/Reference/HcnRegisterGuestNetworkServiceCallback.md)
##### [HcnUnregisterGuestNetworkServiceCallback](./hcn/Reference/HcnUnregisterGuestNetworkServiceCallback.md)
##### [HcnCreateGuestNetworkService](./hcn/Reference/HcnCreateGuestNetworkService.md)
##### [HcnCloseGuestNetworkService](./hcn/Reference/HcnCloseGuestNetworkService.md)
##### [HcnModifyGuestNetworkService](./hcn/Reference/HcnModifyGuestNetworkService.md)
##### [HcnDeleteGuestNetworkService](./hcn/Reference/HcnDeleteGuestNetworkService.md)
#### Port Reservations
##### [HcnReserveGuestNetworkServicePort](./hcn/Reference/HcnReserveGuestNetworkServicePort.md)
##### [HcnReserveGuestNetworkServicePortRange](./hcn/Reference/HcnReserveGuestNetworkServicePortRange.md)
##### [HcnReleaseGuestNetworkServicePortReservationHandle](./hcn/Reference/HcnReleaseGuestNetworkServicePortReservationHandle.md)
##### [HcnEnumerateGuestNetworkPortReservations](./hcn/Reference/HcnEnumerateGuestNetworkPortReservations.md)
##### [HcnFreeGuestNetworkPortReservations](./hcn/Reference/HcnFreeGuestNetworkPortReservations.md)
## JSON Schema
### [JSON Schema Reference](./hcn/HNS_Schema.md)

# [Windows Hypervisor Platform API](./hypervisor-platform/hypervisor-platform.md)
## [WHvCancelRunVirtualProcessor](./hypervisor-platform/funcs/WHvCancelRunVirtualProcessor.md)
## [WHvCreatePartition](./hypervisor-platform/funcs/WHvCreatePartition.md)
## [WHvCreateVirtualProcessor](./hypervisor-platform/funcs/WHvCreateVirtualProcessor.md)
## [WHvDeletePartition](./hypervisor-platform/funcs/WHvDeletePartition.md)
## [WHvDeleteVirtualProcessor](./hypervisor-platform/funcs/WHvDeleteVirtualProcessor.md)
## [WHvGetCapability](./hypervisor-platform/funcs/WHvGetCapability.md)
## [WHvGetPartitionCounters](./hypervisor-platform/funcs/WHvGetPartitionCounters.md)
## [WHvGetPartitionProperty](./hypervisor-platform/funcs/WHvGetPartitionProperty.md)
### [Data Types](./hypervisor-platform/funcs/WHvPartitionPropertyDataTypes.md)
## [WHvGetVirtualProcessorCounters](./hypervisor-platform/funcs/WHvGetVirtualProcessorCounters.md)
## [WHvGetVirtualProcessorInterruptControllerState](./hypervisor-platform/funcs/WHvGetVirtualProcessorInterruptControllerState.md)
## [WHvGetVirtualProcessorRegisters](./hypervisor-platform/funcs/WHvGetVirtualProcessorRegisters.md)
### [Data Types](./hypervisor-platform/funcs/WHvVirtualProcessorDataTypes.md)
## [WHvGetVirtualProcessorXSaveState](./hypervisor-platform/funcs/WHvGetVirtualProcessorXSaveState.md)
## [WHvMapGpaRange](./hypervisor-platform/funcs/WHvMapGpaRange.md)
## [WHvQueryGpaRangeDirtyBitmap](./hypervisor-platform/funcs/WHvQueryGpaRangeDirtyBitmap.md)
## [WHvRequestInterrupt](./hypervisor-platform/funcs/WHvRequestInterrupt.md)
## [WHvResumePartitionTime](./hypervisor-platform/funcs/WHvResumePartitionTime.md)
## [WHvRunVirtualProcessor](./hypervisor-platform/funcs/WHvRunVirtualProcessor.md)
### [Exit Contexts](./hypervisor-platform/funcs/WHvExitContextDataTypes.md)
### [Memory Access](./hypervisor-platform/funcs/MemoryAccess.md)
### [I/O Port Access](./hypervisor-platform/funcs/IOPortAccess.md)
### [MSR Access](./hypervisor-platform/funcs/MSRAccess.md)
### [CPUID Access](./hypervisor-platform/funcs/CPUIDAccess.md)
### [Virtual Processor Exception](./hypervisor-platform/funcs/VirtualProcessorException.md)
### [Interrupt Window](./hypervisor-platform/funcs/InterruptWindow.md)
### [Unsupported Feature](./hypervisor-platform/funcs/UnsupportableFeature.md)
### [Execution Cancelled](./hypervisor-platform/funcs/ExecutionCancelled.md)
## [WHvSetPartitionProperty](./hypervisor-platform/funcs/WHvSetPartitionProperty.md)
### [Data Types](./hypervisor-platform/funcs/WHvPartitionPropertyDataTypes.md)
## [WHvSetupPartition](./hypervisor-platform/funcs/WHvSetupPartition.md)
## [WHvSetVirtualProcessorInterruptControllerState](./hypervisor-platform/funcs/WHvSetVirtualProcessorInterruptControllerState.md)
## [WHvSetVirtualProcessorRegisters](./hypervisor-platform/funcs/WHvSetVirtualProcessorRegisters.md)
### [Data Types](./hypervisor-platform/funcs/WHvVirtualProcessorDataTypes.md)
## [WHvSetVirtualProcessorXSaveState](./hypervisor-platform/funcs/WHvSetVirtualProcessorXSaveState.md)
## [WHvSuspendPartitionTime](./hypervisor-platform/funcs/WHvSuspendPartitionTime.md)
## [WHvTranslateGva](./hypervisor-platform/funcs/WHvTranslateGva.md)
## [WHvUnmapGpaRange](./hypervisor-platform/funcs/WHvUnmapGpaRange.md)

# Virtualization Related Tools
## [Virtual Hard Disk Interface](https://docs.microsoft.com/windows/win32/api/virtdisk/)

## [Hypervisor Instruction Emulator API](./hypervisor-instruction-emulator/hypervisor-instruction-emulator.md)
### Instruction Emulation
#### [I/O Port Access](./hypervisor-instruction-emulator/funcs/IOPortAccessIE.md)
#### [MMIO Access](./hypervisor-instruction-emulator/funcs/MMIOAccessIE.md)
### Emulator Structures
#### [WHV_EMULATOR_CALLBACKS](./hypervisor-instruction-emulator/funcs/WhvEmulatorCallbacks.md)
#### [WHV_EMULATOR_IO_ACCESS_INFO](./hypervisor-instruction-emulator/funcs/WhvEmulatorIOAccessInfo.md)
#### [WHV_EMULATOR_MEMORY_ACCESS_INFO](./hypervisor-instruction-emulator/funcs/WhvEmulatorMemoryAccessInfo.md)
#### [WHV_EMULATOR_STATUS](./hypervisor-instruction-emulator/funcs/WhvEmulatorStatus.md)
### API Methods
#### [WHvEmulatorCreateEmulator](./hypervisor-instruction-emulator/funcs/WHvEmulatorCreateEmulator.md)
#### [WHvEmulatorDestoryEmulator](./hypervisor-instruction-emulator/funcs/WHvEmulatorDestoryEmulator.md)
#### [WHvEmulatorTryIoEmulation](./hypervisor-instruction-emulator/funcs/WHvEmulatorTryEmulation.md)
#### [WHvEmulatorTryMmioEmulation](./hypervisor-instruction-emulator/funcs/WHvEmulatorTryEmulation.md)
### Callback Functions
#### [WHV_EMULATOR_GET_VIRTUAL_PROCESSOR_REGISTERS_CALLBACK](./hypervisor-instruction-emulator/funcs/WHvEmulatorGetVirtualProcessorRegistersCallback.md)
#### [WHV_EMULATOR_IO_PORT_CALLBACK](./hypervisor-instruction-emulator/funcs/WHvEmulatorIOPortCallback.md)
#### [WHV_EMULATOR_MEMORY_CALLBACK](./hypervisor-instruction-emulator/funcs/WHvEmulatorMemoryCallback.md)
#### [WHV_EMULATOR_SET_VIRTUAL_PROCESSOR_REGISTERS_CALLBACK](./hypervisor-instruction-emulator/funcs/WHvEmulatorSetVirtualProcessorRegistersCallback.md)
#### [WHV_EMULATOR_TRANSLATE_GVA_PAGE_CALLBACK](./hypervisor-instruction-emulator/funcs/WHvEmulatorTranslateGVAPageCallback.md)

## VM Saved State Dump Provider API
### [Overview](./vm-dump-provider/index.md)
### [Reference](./vm-dump-provider/reference/reference.md)
### [Samples](./vm-dump-provider/samples.md)
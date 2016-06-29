# G3.1.3.14_EnergyPlus-PIU-Sec-Flow-Calculator
tool can be used to automatically  update  'Maximum Secondary Air Flow Rate' input field in
AirTerminal:SingleDuct:ParallelPIU:Reheat object to meet the requirements of G3.1.3.14. The tool
obtains autosized 'Maximum Primary Air Flow Rate' from the eio file and updates 'Maximum Secondary
Air Flow Rate' in input data file as 50% of the 'Maximum Primary Air Flow Rate'. Using file
comparison utility such as WinMerge/WinDiff etc., original and updated input files can be compared
with data provided in the Output tab to verify the results. For models with large number of zones,
this tool may save users much of the time and hassles so that they can make changes in input files
without worrying about the G3.1.3.14 compliance.
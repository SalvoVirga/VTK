set(Module_SRCS
  vtkAddMembershipArray.cxx
  vtkAdjacencyMatrixToEdgeTable.cxx
  vtkArrayNorm.cxx
  vtkArrayToTable.cxx
  vtkCollapseGraph.cxx
  vtkCollapseVerticesByArray.cxx
  vtkContinuousScatterplot.cxx
  vtkDataObjectToTable.cxx
  vtkDotProductSimilarity.cxx
  vtkExtractSelectedTree.cxx
  vtkEdgeCenters.cxx
  vtkExpandSelectedGraph.cxx
  vtkExtractSelectedGraph.cxx
  vtkGenerateIndexArray.cxx
  vtkGraphHierarchicalBundleEdges.cxx
  vtkGroupLeafVertices.cxx
  vtkMergeColumns.cxx
  vtkMergeGraphs.cxx
  vtkMergeTables.cxx
  vtkMutableGraphHelper.cxx
  vtkNetworkHierarchy.cxx
  vtkPipelineGraphSource.cxx
  vtkPruneTreeFilter.cxx
  vtkRandomGraphSource.cxx
  vtkReduceTable.cxx
  vtkRemoveIsolatedVertices.cxx
  vtkSparseArrayToTable.cxx
  vtkStreamGraph.cxx
  vtkStringToCategory.cxx
  vtkStringToNumeric.cxx
  vtkTableToArray.cxx
  vtkTableToGraph.cxx
  vtkTableToSparseArray.cxx
  vtkTableToTreeFilter.cxx
  vtkThresholdGraph.cxx
  vtkThresholdTable.cxx
  vtkTransferAttributes.cxx
  vtkTransposeMatrix.cxx
  vtkTreeFieldAggregator.cxx
  vtkTreeDifferenceFilter.cxx
  vtkTreeLevelsFilter.cxx
  vtkVertexDegree.cxx
  vtkRemoveHiddenData.cxx
  vtkKCoreDecomposition.cxx
  )

vtk_module_library(vtkInfovisCore ${Module_SRCS})

SET(Module_SRCS
  vtkAVSucdReader.cxx
  vtkBYUReader.cxx
  vtkBYUWriter.cxx
  #vtkCGMWriter.cxx # Needs vtkViewport.
  vtkChacoReader.cxx
  vtkFacetWriter.cxx
  vtkFLUENTReader.cxx
  vtkGAMBITReader.cxx
  vtkGaussianCubeReader.cxx
  vtkHoudiniPolyDataWriter.cxx
  vtkIVWriter.cxx
  vtkMCubesReader.cxx
  vtkMCubesWriter.cxx
  vtkMFIXReader.cxx
  vtkMoleculeReaderBase.cxx
  vtkOBJReader.cxx
  vtkOpenFOAMReader.cxx
  vtkParticleReader.cxx
  vtkPDBReader.cxx
  vtkProStarReader.cxx
  vtkPTSReader.cxx
  vtkSTLReader.cxx
  vtkSTLWriter.cxx
  vtkTecplotReader.cxx
  vtkWindBladeReader.cxx
  vtkXYZMolReader.cxx
  )

if (NOT VTK_LEGACY_REMOVE)
  # only add those classes if not removing legacy code.
  list(APPEND Module_SRCS
    vtkUGFacetReader.cxx)
endif()

vtk_module_library(vtkIOGeometry ${Module_SRCS})

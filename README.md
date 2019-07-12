# FMOD6.57Wrapper
A wrapper around FMOD6.75

This is a very neat tidy wrapper around FMOD6.75. This doesn't reprodue the C++ Wrapper that comes out of the box with FMOD. This is a game related wrapper that simplifies the API for rapid game development

#### dependence 
##### tinyxml
download the tinyxml source code and use vs2010 build. get libs and includes
##### boost
get source code from www.boost.org. after unzip, and run bootstrap.bat，gen bjam.exe，cd  boost root dir，input bjam --toolset=msvc-10.0 --build-type=complete stage  start compile(VS2010). The file gen in stage dir.
##### luabind
luabind offical download：http://www.rasterbar.com/products/luabind.html

unzip and start compile luabind

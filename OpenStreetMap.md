classDiagram
direction BT
class OpenStreetMap {
  + OpenStreetMap(String) 
  + processWay(Element) Unit
  + processNode(Element) Unit
  + parseXML(String) Unit
  + GeographicGraph cyclableGraph
  + String filename
}


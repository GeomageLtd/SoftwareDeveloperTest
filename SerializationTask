//Please find bugs, refactor code and follow instraction in comments
#include <iostream>
#include <vector>

struct Point
{
    Point(int i_x, int i_y): x(i_x), y(i_y){}
    int x = 0;
    int y = 0;
};

struct Shape
{
    Shape() = delete;
    virtual Draw() = 0; // should print in std out all members
};

struct Circle : public Shape
{
    Circle(Point center, int radius ):m_center(center), m_radius(radius) {};
private:
    Point m_center;
    int m_radius;
};

struct Polygon : public Shape
{
    Polygon(std::vector<Point> vertices):m_vertices(vertices)
    {
    }
 
private:
    std::vector<Point> m_vertices;
};


int main()
{
    std::vector<Shape*> dataStored;
    std::vector<Shape*> dataRestored;
    //Create 10 random different Shapes;
    //save it on disk 
    //read from disk
    //check 
    return 0;
}

import React from 'react'
import ReactDOM from 'react-dom'

const App = () => {
  const course = 'Half Stack application development'
  const part1 = 'Fundamentals of React'
  const exercises1 = 10
  const part2 = 'Using props to pass data'
  const exercises2 = 7
  const part3 = 'State of a component'
  const exercises3 = 14
  const Header = (props)=> {
      return(
          <div>
              <p><h1>{props.course} </h1> </p>
          </div>
      )
  }
  const Content = (props)=> {
    return(
        <div>
            <p>{props.name} : {props.ex}</p>
        </div>
    )
}
const Total = (props)=> {
    return(
        <div>
            <p> {props.name} {props.s}</p>
        </div>
    )
}
  return (
    <div>
      <Header course={course} />
      <Content name= {part1} ex={exercises1}   />
      <Content name= {part2} ex={exercises2}   />
      <Content name= {part3} ex={exercises3}   />
      <Total   name="Total :" s={exercises1 + exercises2 + exercises3}  />
    </div>
  )
}

ReactDOM.render(<App />, document.getElementById('root'))

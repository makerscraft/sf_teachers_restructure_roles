## Proposal

Refactor existing implementations of PhaseLead and FloatingTeacher

> Restructure Phase Lead, Floating Teacher TO Teacher, Phase Teacher and
> Floating Teacher.  All full time are Teachers - and most will also be Phase
> Teacher and Floating Teacher.  Several accountabilities have been added to
> Teacher from the old Phase Teacher, and some accountabilities have been moved
> to Phase Teacher or Floating Teacher

## Interpreted Changes:

  * Extract class: Teacher
  * Rename class: PhaseLead -&gt; PhaseTeacher
  * Extract mixin: PhaseLeadMixin
  * Extract mixin: PhaseTeacherMixin

## Proposer

Anne Spalding
